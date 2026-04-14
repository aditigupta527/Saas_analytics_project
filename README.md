# SaaS Startup Growth Analytics
### Python | MySQL | Power BI | Excel

---

## Business Problem
A SaaS startup with 2,000 customers had 24 months of data but zero analytics.
Leadership could not answer: How fast are we growing? Which customers are leaving?
Which marketing channels waste money? How much is each customer worth?

---

## What I Built
A complete end-to-end analytics pipeline in 4 phases:

- **Phase 1 (Python):** Simulated 2 years of realistic SaaS data across 5 tables
- **Phase 2 (MySQL):** Wrote 13 SQL queries covering churn, CAC, LTV, cohort analysis
- **Phase 3 (Python + Pandas):** Data cleaning, metric calculation, cohort retention heatmap
- **Phase 4 (Power BI):** 3-page interactive dashboard with DAX measures

---

## Key Findings
- Revenue grew ~12x: from $12,369 to $147,683 MRR in 24 months
- Blended churn rate = 3.3%/month (below industry avg of 5–7%)
- Enterprise customers generate ~14x the LTV of Starter customers
- Organic channel has lowest CAC ($25.86) vs Paid Search ($235.33)

---

## Tech Stack
Python (Pandas, NumPy, Seaborn, Matplotlib) | MySQL | Power BI (DAX)

---

## Files in This Repo

| File | Description |
|------|-------------|
| `saas_analytics_py.ipynb` | Python data generation + EDA + cohort heatmap |
| `saas_analytics_sql.sql` | 13 MySQL business queries |
| `saas_analysis_dashboard.pbix` | Power BI dashboard file |
| `customers.csv` | Customer data |
| `subscriptions.csv` | Subscription data |
| `revenue.csv` | Monthly revenue data |
| `monthly_activity.csv` | User activity data |
| `marketing_spend.csv` | Marketing channel spend data |
| `Business_Problem_Statement_Simple.pdf` | Project brief |
