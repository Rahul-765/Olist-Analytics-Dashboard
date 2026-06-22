# Olist E-Commerce Analytics Dashboard
## Executive Summary
Olist is a Brazilian company that connects small businesses to major online marketplaces. The dataset contains real world e-commerce transactions from 2016–2018 and was made publicly available.

**The dataset includes information about:**
-	Customers – customer IDs, locations (city/state) 
-	Orders – order dates, status, delivery dates 
-	Products – product categories, dimensions, weight 
-	Sellers – seller locations and IDs 
-	Payments – payment type, installments, payment value 
-	Reviews – customer review scores and comments 
-	Order Items – products purchased in each order 
-	Geolocation – ZIP-code-based latitude and longitude da

This dashboard consolidates 8 relational data sources into a single executive intelligence layer across three domains: **commercial performance**, **operational efficiency** and **marketplace health**. 

**[→ Open Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMmI1OTA0MTYtY2M2OS00OTZkLWIwZGUtZGFlMTVkZDBiZmYyIiwidCI6IjQ5NWVkMzcwLWJiYjYtNGY2OC04ZWUwLTkxYzM3NTk5ODZmMiJ9)**

## Key Findings
### Sales & Operations
- A small number of product categories account for a disproportionate share of total revenue 
- Payment method mix reveals clear consumer preferences that inform checkout and partnership strategy
- Weekend vs. weekday order volume shows exploitable demand patterns

### Delivery & Reviews
- On-time delivery rate falls short of best in class e-commerce benchmarks, with late deliveries clustering in specific states
- Customer review scores correlate directly with delivery performance 
- Average shipping time varies significantly by seller state

### Customers & Sellers
- Customer retention rate surfaces a loyalty gap: the majority of buyers are one-time purchasers, representing significant untapped repeat-revenue potential
- Seller revenue is heavily concentrated in the top tier a dependency risk if key sellers churn
- States with longest shipping times also show lowest review scores, confirming geography as the #1 satisfaction driver

## Dashboard Architecture

### Page 1 — Sales & Operations
*Commercial performance and revenue drivers*

| KPI | Description |
|---|---|
| Total Orders | Volume baseline |
| Total Revenue | GMV across the period |
| Average Order Value | Basket size health |
| Freight Cost | Fulfilment cost as a component of revenue |
| Payment Method Mix | Consumer payment behaviour |

### Page 2 — Delivery & Reviews
*Fulfilment efficiency and customer satisfaction*

| KPI | Description |
|---|---|
| On-Time Delivery % | SLA performance |
| Late Deliveries | Volume and geographic distribution |
| Avg. Processing Time | Warehouse-to-dispatch efficiency |
| Avg. Shipping Time | Dispatch-to-delivery by region |
| Average Review Score | Proxy NPS by category and seller |

### Page 3 — Customers & Sellers
*Marketplace growth and ecosystem health*

| KPI | Description |
|---|---|
| Returning Customers | Retention signal |
| Customer Retention Rate | Loyalty baseline |
| Active Sellers | Supply-side health |
| Seller Revenue Distribution | Concentration risk monitor |
| Freight Cost vs. Sales by State | Regional margin analysis |
