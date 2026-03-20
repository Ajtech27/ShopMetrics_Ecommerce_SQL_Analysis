 ## ShopMetrics E-Commerce Sales Analysis
**Domain:** E-Commerce Analytics

A full e-commerce sales analysis for a fictional retailer — ShopMetrics — with 500 customers, 60 products, and 5,200 orders across 2022 and 2023.

**Dataset — 4 Tables:** products · customers · orders · order_items (10,994 line items)

**12 Analytical Queries:**

| # | Query | Techniques |
|---|---|---|
| 1 | Monthly Revenue & Order Trends | GROUP BY, aggregates, date functions |
| 2 | Year-over-Year Growth by Month | CTE, self-JOIN, growth % calculation |
| 3 | Top 10 Products by Revenue & Profit | RANK() window function, margin % |
| 4 | Category Performance Summary | SUM() OVER() for revenue share % |
| 5 | Regional Sales Analysis | Multi-table JOIN, revenue per customer |
| 6 | Customer Segmentation | CTE, CASE WHEN tiers, loyalty segments |
| 7 | Top 10 Customers by Lifetime Value | Multi-JOIN, date range, LTV calc |
| 8 | Payment Method by Region | PARTITION BY window, % of region |
| 9 | Discount Impact Analysis | CASE WHEN bands, margin erosion |
| 10 | Refund & Cancellation Rate | Conditional aggregation |
| 11 | Rolling 3-Month Moving Average | ROWS BETWEEN window frame |
| 12 | Executive KPI Summary | Single-query stakeholder dashboard |

**Tools:** PostgreSQL · CTEs · Window Functions · Aggregate Functions · Multi-table JOINs
