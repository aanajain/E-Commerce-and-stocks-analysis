# E-Commerce & Stock Market Analytics Dashboard

## Project Overview
A real-world data analytics project analyzing e-commerce sales data and stock market trends for the period 2010–2011. Built using SQL for data extraction and Tableau for interactive visualization.

## Live Dashboard
[View Interactive Dashboard](https://public.tableau.com/app/profile/aana.jain/viz/e-commerceanalysis_17792343630790/Dashboard2?publish=yes)

## Datasets Used
- **UCI Online Retail Dataset** — 541,909 real transactions from a UK-based online retail store (Kaggle)
- **Yahoo Finance Stock Data** — Historical monthly stock prices for AMZN, WMT, TGT (2010–2011)

## Tools & Technologies
- **SQL** — SQLiteOnline for data extraction and analysis
- **Tableau Public** — Interactive dashboard creation
- **Excel/Google Sheets** — Data cleaning and CSV conversion

## Key Insights
- Total revenue of £10.6 million across 2,079 orders
- United Kingdom accounts for over 85% of total revenue
- Amazon stock price grew 41% from 2010 to 2011
- Revenue peaks in Q4 (October–December) due to holiday shopping season
- Strong correlation between e-commerce revenue growth and Amazon stock price movement

## SQL Concepts Used
- SELECT, WHERE, GROUP BY, ORDER BY
- Aggregate functions — SUM, AVG, COUNT, MAX, MIN
- SUBSTR for date extraction
- Calculated fields and JOIN operations

## Dashboard Features
- KPI cards showing Total Revenue, Total Orders, Avg Order Value, Return Rate
- Monthly Revenue trend (2010 vs 2011)
- Amazon Stock Price trend (2010 vs 2011)
- Top 10 Products by Revenue
- Revenue by Country

## Project Structure
```
ecommerce-stock-analytics/
│
├── data/
│   ├── online_retail.csv
│   ├── amzn_us_d.csv
│   ├── wmt_us_m.csv
│   └── tgt_us_m.csv
│
├── sql/
│   └── queries.sql
│
├── dashboard/
│   └── e-commerceanalysis.twbx
│
└── README.md
```

## Author
**Aana Jain**
Built as a beginner data analytics portfolio project covering SQL, Tableau and real-world dataset analysis.

---
