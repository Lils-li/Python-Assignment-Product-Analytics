Description

Analysis of customer and order data:

Files: pa_customers.csv and pa_orders.csv
Goal: identify key metrics, customer behavior, segments, and actionable recommendations
Data
customers — 1,400 entries: id, signup date, country, acquisition channel, device, plan
orders — 5,000 entries: order id, customer id, timestamp, category, quantity, price, discount, revenue, status, payment method
Steps
Data cleaning: convert dates, fix negative quantities, handle missing values
Merge tables: merged dataframe, 46 customers with no orders
KPI & segments:
Total revenue: 2,054,772
Orders (Completed): 4,514
Unique customers: 1,338
AOV: 455.2
Analysis by acquisition channel, product category, device, country
Cohort analysis: retention by months since first purchase
Repeat purchase rate: ~45% of customers made 2+ orders
Key Insights
Almost all customers place at least 1 order → focus on retention & repeat purchases
High AOV → valuable transactions
Risky but profitable categories: Electronics, Sports
Top-performing channels by AOV: Email, Referral
iOS generates slightly more revenue than Android and Web
