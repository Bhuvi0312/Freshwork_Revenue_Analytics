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

## Visualizations in Power BI
### 1.Net Revenue by Region Over Time
Line chart to observe revenue trends across regions monthly.

### 2.Plan Preferences Over Months
Stacked column chart showing which plans are favored by customers.

### 3.Average Discount% by Product
Bar chart visualizing discounting behavior across the product portfolio.

### 4.Cross-Sell Revenue by Region
Bar chart tracking regions that perform best in cross-sell opportunities.

### 5.Discount% Trend Over Time
Line chart monitoring how discounts vary month-to-month.

### 6.Customer Behavior Slicers
Interactive filters for PLAN, PRODUCT, REGION.

## Assumptions Made
=> The first product sold to a customer is treated as a base product.

=> Any subsequent product purchases by the same customer are categorized as cross-sell.

=> The MONTHYEAR field is treated as the first day of the month for temporal analysis.

## Recommendations
=> Focus marketing efforts on high-performing plans with lower average discounts.

=> Analyze underperforming regions and provide sales training or strategy shifts.

=> Promote cross-sell campaigns in regions with lower adoption rates.

=> Collect additional fields such as customer tenure, industry, and usage frequency in future datasets.

## Tools & Technologies Used
=> Power BI – Dashboard and interactive reporting

=> Python / Pandas – Data cleaning, transformation, and metric generation

=> Excel / CSV – Source file format

=> GitHub – (Optional) Version control and documentation

## Future Enhancements
### Adding More Data Fields
→ E.g., Customer industry, size, churn status, contract length, or support usage.

### Predictive Analytics
=> Use machine learning to forecast:
  > Customer churn
  > Lifetime value (LTV)
  > Product upgrade probability

### Automated Data Refresh
→ Automate monthly data uploads into Power BI using Power Query or Python scripts.

### User Segmentation
→ Group customers by usage patterns, region, or value tiers to target more effectively.

### Real-Time Dashboard
→ Integrate with a live database to reflect real-time performance metrics.

### Mobile-Optimized Power BI Dashboard
→ Make the report responsive for mobile viewing.




