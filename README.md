# Product / Sales / Marketing Analytics

## Description
Analysis of customer and order data to identify key metrics, customer behavior, segments, and actionable recommendations.  
Files: `pa_customers.csv`, `pa_orders.csv`

## Data
- **customers**: 1,400 entries (id, signup date, country, acquisition channel, device, plan)  
- **orders**: 5,000 entries (order id, customer id, timestamp, category, quantity, price, discount, revenue, status, payment method)  

## Steps
1. Clean data: convert dates, fix negative quantities, handle missing values  
2. Merge tables into `merged` dataframe  
3. Compute KPIs: total revenue, orders, unique customers, AOV  
4. Analyze by acquisition channel, product category, device, and country  
5. Cohort analysis: retention by months since first purchase  
6. Repeat purchase rate and customer segmentation  

## Key Insights
- Nearly all customers place at least 1 order → focus on retention & repeat purchases  
- High AOV indicates valuable transactions  
- Risky but profitable categories: Electronics, Sports  
- Top-performing channels by AOV: Email, Referral  
- iOS generates slightly more revenue than Android and Web
