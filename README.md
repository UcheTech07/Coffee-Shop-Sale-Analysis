# Coffee-Shop-Sale-Analysis
## Overview
Maven Roasters is a fictional coffee shop with three locations across New York City. This project focuses on analyzing its transaction data, including timestamps, location details, and product-level information. The goal is to uncover insights into sales performance and customer behavior by exploring trends in transactions, product popularity, and ordering patterns.The dashboard is designed to help stakeholders monitor performance, boost operational efficiency, and enhance customer experience across all Maven Roasters locations.
## Objective Questions
- How have Maven Roasters sales trended over time?
- Which days of the week tend to be busiest, and why do you think that's the case?
- Which products are sold most and least often? Which drive the most revenue for the business?
## Data Structure
The dataset is a is a .csv file which contains 149,116 rows of data with column names:
- Transaction_ID : Which shows the unique ttansaction id of items ordered
- Transaction_date : Which showed the date the items where ordered
- Transaction_time : Showed what time the item was orderd
- transaction_qty : Show the total quantity of items ordered for each transaction
- Unit_price : The price at which each item was sold
- product_category : Show what category the item ordered belonged to
- product_type : The type of product ordered
- Product_detail : Showed detail of the product type ordered.
## Data Cleaning and Analysis
Microsoft Excel was used in the data cleaning and analysis 
### Steps
1. Checked for duplicates, which there were none.
2. Checked for blanks and nulls, Which there where also no null values.
3. Checked if each columns where in the right format.
4. Extracted columns for Weekday and Month from the transaction_date column
5. Extracted the hour_of_day column from the transaction_time column.
6. Analysis was carried out using pivot tables.
7. Visualization was done using pivot charts.
## Analysis Results
- **Total Revenue generated,Total orders**:A comprehensive evaluation, focusing on key metrics such as Total Revenue, Count of Orders
- **Monthly and Daily Sales Revenue**: Analyzed sales trends across different months and days.
- **Top selling product category**: An evaluation of the product categories with the most generated revenue
- **Order Distribution by Coffee Type**: An analysis of the distribution of orders across different coffee types
- **Peak Day and Hour**: An analysis to identify the hours and days with the highest revenue
## Dashboard
![image](https://github.com/user-attachments/assets/c014e4b0-dcd2-478d-9d02-1702e7f67adf)
## Summary
The Total Revenue generated across the three store location was 669K, a total of 149K orders was placed, Monday was the best selling days and sales tend to peak around 10am, about 56% of sales occur during the morning period
