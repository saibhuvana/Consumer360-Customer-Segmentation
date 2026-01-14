# Consumer360-Customer-Segmentation
Customer Segmentation &amp; CLV Engine
# Consumer360 – Customer Segmentation & CLV Engine

## Project Overview
Consumer360 is an end-to-end customer analytics project designed to help an e-commerce business identify high-value customers and churn-risk customers using RFM (Recency, Frequency, Monetary) segmentation and interactive dashboards.

The project addresses the problem of generic and ineffective marketing campaigns by enabling targeted customer engagement and retention strategies.

---

## Business Problem
Many e-commerce companies run broad marketing campaigns without understanding customer value. This leads to poor retention and loss of high-value customers.

Consumer360 solves this problem by:
- Identifying Champion customers for premium engagement
- Detecting Churn Risk customers for targeted retention
- Providing business-ready insights through dashboards

---

## Tech Stack
- Python (Pandas, NumPy)
- Google Colab
- Power BI Desktop
- Excel / CSV
- GitHub

---

## Dataset Information
- Total Records: 392,692
- Total Columns: 14
- E-commerce transactional data

Key Columns:
- InvoiceNo
- CustomerID
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- Country
- Revenue
- Year, Month, Week

---

## Core Analytics Logic

### RFM Segmentation
RFM stands for:
- Recency – How recently a customer made a purchase
- Frequency – How often a customer purchases
- Monetary – How much the customer spends

Each metric is scored on a 1–5 scale and customers are segmented into:
- Champions
- Loyal Customers
- Potential Loyalists
- At Risk
- Churn Risk
- Hibernating
- Recent Customers

---

## Power BI Dashboard Features
- Customer segment distribution
- RFM matrix visualization
- Country-wise revenue analysis
- Interactive slicers for filtering customer segments
- Business-ready insights

---

## Project Structure
Consumer360-Customer-Segmentation/
│
├── data/
│   ├── Retail_cleaned.xlsx
│   ├── RFM_Output.csv
│
├── notebooks/
│   └── RFM_Analysis.ipynb
│
├── powerbi/
│   └── Consumer360_Dashboard.pbix
│
├── README.md

---

## Key Business Insights
- Identified high-value customers for premium marketing
- Detected churn-risk customers early
- Improved customer retention strategies
- Enabled data-driven marketing decisions

---

## Future Enhancements
- Predictive Customer Lifetime Value (CLV) modeling
- Automated weekly data refresh
- Cohort analysis
- Market Basket Analysis
- Power BI Service deployment

---

## Learning Outcomes
- Hands-on experience with real-world data
- Customer segmentation using RFM analysis
- Python data analysis and preprocessing
- Power BI dashboard creation
- End-to-end analytics project implementation

---

## Author
Bhuvana Surya

---

## Note
Power BI (.pbix) file may exceed GitHub size limits. Dashboard screenshots or access can be provided upon request.
