# boAt-Sales-Analytics-Dashboard

# 🎯Overview
This project focuses on analysing boAt's sales data using Power BI to understand overall business performance, product profitability, customer behaviour, sales channel performance, and regional trends. An interactive dashboard was developed to transform sales data into meaningful insights and support data-driven business decisions.

# ❓Business Problem
- How do sales trends change over time?
- Which products and categories contribute the most to revenue and profit?
- Which regions generate the highest sales?
- Which sales channels perform best in terms of order volume?
- Which customer segments contribute the most to sales?
- How do discounts, returns, and cancellations affect business performance?

# 🗂️Dataset
The dataset was obtained from Kaggle: boAt Sales Analytics Dataset by Arjun Gupta.
Source link : https://www.kaggle.com/datasets/arjunguptadatanalyst/boat-sales-analytics-dataset-arjun-gupta?select=Sales_Channel.csv

It contains five CSV files:
- Sales_Data.csv – Sales transactions, revenue, discounts, profit, and order details.
- Customer_Details.csv – Customer demographics, segments, tiers, and locations.
- Product_Details.csv – Product categories, brands, pricing, and product attributes.
- Sales_Channel.csv – Sales channel information and channel types.
- Delivery_Partner_Data.csv – Delivery partner details and performance-related attributes.

# 🛠️Tools & Technologies
- Power BI Desktop – Dashboard development and data visualization
- Power Query – Data cleaning and transformation
- DAX – Measures and business calculations
- Data Modelling – Star schema and table relationships

# 🧹Data Cleaning
- Imported and examined the five CSV files.
- Checked data types, column formats, and data consistency.
- Reviewed missing values and retained blanks where they represented valid business scenarios, such as cancellation or return reasons for orders that were not cancelled or returned.
- Ensured appropriate data types for numerical, categorical, and date fields.
- Formatted percentage-based fields, such as discounts, appropriately.
- Prepared the tables for data modelling and dashboard analysis.

# 🧮DAX Measures
- Total Net Sales – Calculates total net sales revenue.
- Total Profit – Calculates total profit.
- Profit Margin % – Measures profit as a percentage of net sales.
- Total Orders – Counts distinct sales orders.
- Total Quantity Sold – Calculates the total quantity sold.
- Average Discount % – Calculates the average discount percentage.
- MoM Sales Growth % – Measures month-over-month sales growth.
- Return Rate % – Measures the proportion of returned orders.
- Cancellation Rate % – Measures the proportion of cancelled transactions.

# 💡Key Findings
- Achieved ₹4.29B in sales with a 13.61% profit margin.
- boAt Airdopes 141 was the top-selling product.
- True Wireless Earbuds led category sales.
- Online marketplaces contributed 61.24% of orders.
- The North region recorded the highest sales.
- Tier-1 customers contributed 41.37% of sales.
- Average discount reached 40.94%.
- Returns accounted for approximately 4.66% of transactions.

# 🚀Recommendations
- Optimise discounts to improve profit margins.
- Focus on high-performing and profitable products.
- Strengthen online sales channels.
- Target valuable customer segments.
- Improve regional inventory planning.
- Reduce returns and cancellations.
