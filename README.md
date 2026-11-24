# Product Launch Performance Analysis (Python, SQL & Excel)

## Business Objective
Analyze **112,101 e-commerce transactions** across **32,729 newly launched SKUs** from the Brazilian E-Commerce Public Dataset (Olist) to identify drivers of successful product launches, diagnose post-launch revenue drop-offs, and formulate data-backed pricing and marketing strategies.

## Key Portfolio KPIs
- **Total Unique Products Launched:** 32,729 SKUs
- **Completed Sales Volume:** 112,101 units
- **Total Portfolio Revenue:** $13,494,400.74
- **Average Selling Price (ASP):** $120.38
- **Overall Customer Satisfaction Rating:** 4.05 / 5.0

## Repository Structure
- `notebooks/Product_Launch_Performance_Analysis.ipynb`: End-to-end Google Colab notebook covering data cleaning, IQR outlier flagging, launch-window cohort engineering, and visualizations.
- `sql/product_launch_queries.sql`: Standalone SQL queries utilizing `GROUP BY`, CTEs, subqueries, and `RANK()` window functions.
- `data/`: Cleaned dataset and aggregated category/monthly performance summary tables.
- `reports/Final_Product_Launch_Performance_Report.pdf`: Executive business report with strategic recommendations.
- `visuals/`: Exported high-resolution charts (`monthly_revenue_trend.png`).

## Strategic Recommendations
1. **Front-Load First 30-Day Launch Marketing:** The initial 30-day launch phase captures **$6.81M** in revenue at a **$135.63 AOV** (compared to $107.99 AOV post-launch). Concentrate paid acquisition within the first month of release.
2. **Deploy Day-30 Retention Campaigns:** Automate cross-sell and remarketing workflows at Day 30 to counteract Month-1 sales decay observed in high-ticket tech categories.
3. **14-Day Quality & Review Audits:** Trigger early supplier and listing audits for high-velocity SKUs scoring below 3.5 stars to protect brand equity and repeat conversion.
