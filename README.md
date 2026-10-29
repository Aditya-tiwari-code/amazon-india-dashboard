# Amazon India Sales Dashboard

An Excel management dashboard that gives a non-technical manager a one-page view of Amazon India sales performance: sales, profit, products, orders, payments, fulfilment and geography.

![Dashboard](dashboard.png)

## Business Objective
Help management quickly understand overall business performance and make better decisions, using simple KPIs and charts instead of raw data.

## Dashboard Sections
1. **Overall Sales & Profit Performance**: Total Sales, Total Profit, Total Orders, Units Sold, Average Order Value, Profit Margin %, and a monthly sales and profit trend.
2. **Category & Product Performance**: category-wise sales, profit and units sold, plus the Top 10 products by sales.
3. **Order Status & Revenue Loss**: delivered, shipped, returned and cancelled orders, return and cancellation rates, and category-wise returns and cancellations.
4. **Payment, Fulfilment & Geographic Performance**: sales and profit by payment method, by fulfilment method and by state, plus state-wise orders.

## Key Findings
- Total sales of **₹15.58 Cr** and profit of **₹3.32 Cr** (21.3% margin) from 10,000 orders and 24,926 units; average order value is about ₹15,579.
- Over the last 12 months, sales are **6.5% higher** and profit **8.9% higher** than the 12 months before.
- **Electronics & Mobiles** drives about 79% of sales.
- Returns and cancellations lost about **₹1.56 Cr** (around 10% of sales value). Return rate is 4.9% and cancellation rate is 5.0%.
- **UPI** is the top payment method, **Amazon FBA** is the top fulfilment method, and **Maharashtra** is the top state.

## How the Workbook Is Organised
| Sheet | Purpose |
|---|---|
| Dashboard | The one-page management view (KPIs, charts, insights) |
| Calc | Formula-based tables that feed every chart |
| Data | Original order-level data (10,000 rows) |

All numbers are live Excel formulas, so the dashboard updates if the data changes.

## Notes
- Total Sales includes returned and cancelled orders; revenue lost to them is shown separately.
- Returned and cancelled orders carry zero profit in the source data.
- Return and cancellation rates are shares of total order count.
- Charts show values in ₹ Lakh; KPI cards use ₹ Crore.

## Tools
Microsoft Excel (formulas and native charts)
