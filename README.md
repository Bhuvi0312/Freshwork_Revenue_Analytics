# Freshwork_Revenue_Analytics
## Project Overview
Freshlytics is a Revenue Operations Analytics dashboard designed to uncover actionable insights from sales data across various regions and products for Freshworks. The project focuses on analyzing discounting behavior, plan preferences, cross-sell performance, and customer purchasing patterns over time. It empowers sales and management teams to make data-driven decisions for improved revenue growth and customer engagement.

## Dataset Description
The dataset (Freshwork_data.csv) contains simulated but realistic transaction-level data with the following fields:

### Column Name	and Description
MONTHYEAR: Month and year of the transaction
PLAN_NAME: Subscription plan purchased by the customer
CustomerID: Unique identifier of the customer
REGION: Region/team that executed the sale
PRODUCT: Product sold
NET REVENUE: Final revenue received after discount
Gross Revenue: Listed revenue before discount

## Project Objectives
=> Analyze net revenue trends across months and regions.

=> Identify popular plans and products over time.

=> Evaluate discounting behavior across plans and products.

=> Measure cross-sell performance by region and team.

=> Track customer behavior metrics such as repeat purchases and plan transitions.

=> Recommend improvements for sales strategy and product adoption.

## Key Metrics Created
### Metric	Definition
Discount%:	(Gross Revenue - Net Revenue) / Gross Revenue * 100
Month_Date:	Parsed monthly date for time-based visualizations
Sell Type:	Classified as Base or Cross based on customer’s first product
Cross-Sell: Revenue	Sum of Net Revenue from products sold after the first product to the same customer
