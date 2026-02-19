# Sales Perfromance Analysis
This project explore sales data to understand business performance, identify key drivers of revenue, and provide actionable recommendations. This project demonstrates end-to-end data analysis workflow—from data cleaning to insight generation.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Tools Used](#tools-used)
- [Dataset Overview](#dataset-overview)
- [Data Cleaning Process](#data-cleaning-process)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)

---

## Project Overview
This project is intended for educational and research purposes.
This project contains sales data to understand business performance, identify key drivers of revenue, and provide actionable recommendations. This project demonstrates end-to-end data analysis workflow—from data cleaning to insight generation.

> File Name



Resturant.csv

> Columns

* Order ID: A unique identifier for each sales order. This can be used to track individual transactions.

* Order Date: The date when the order was placed. This column is essential for time-series analysis, such as identifying sales trends over time or seasonality.

* Product: The name or type of the product sold. This column is crucial for analyzing sales performance by product category.

* Price : The unit price of the product. This, along with 'Quantity Ordered', is used to calculate the total price of each order.

* Quantity : The number of units of the product sold in a single order. This is a key metric for calculating revenue and understanding sales volume.

* Purchase Type : The order was made online or in-store or drive-thru.

* Payment Method : How the payment for the order was done.

* Manager : Name of the manager of the store.

* City : The location of the store. This can be used for geographical analysis of sales, such as identifying top-performing regions or optimizing logistics.

> Potential Use Cases:

* Total order and total revenue made

* Most Preferred Payment Method

* Most Selling Product - By Quantity & By Revenue

* Which city had highest revenue

* which manager performed the best(highest sales)

* Average Revenue.

* Is revenue increasing or decreasing over time

* Average Quantity Sold(done)

* Highest purchasing type by orders

* Which city had maximum revenue

---
## Data Source

- Kaggle.com
  
## Tools Used

- *Microsoft Excel* – For further cleaning, Data Collection
- *Power BI* – For Data Visualizations & Reporting 
- *GitHub* – For documentation and version control

## Data Cleaning Process
 
> Overview

This document outlines the data cleaning process applied to the Resturant Sales performance to ensure data quality and consistency for analysis.

> Dataset Information

- Original File: Resturant.csv
- Rows: 254 rows
- Columns: 10 Columns

> Data Cleaning Steps

1. Initial Assessment
   
Checked dataset structure and dimensions
Identified data types for each column
Located missing values and inconsistencies

3. Missing Values Handling
   
No significant missing values found in this dataset
Strategy: If missing values were present, would use appropriate imputation or removal based on column importance

4. Duplicate Records
   
Checked for duplicate  entries
Handled missing values and duplicates (some managers names were duplicated with space so i was able to fix and correct the spaces found in this column)

---
## Dashboard
<img width="869" height="484" alt="front page" src="https://github.com/user-attachments/assets/54330dab-3063-4dc4-8405-fe623d3cfe97" />
<img width="1055" height="499" alt="dash" src="https://github.com/user-attachments/assets/48d61001-6a30-4678-8318-3942f20bfc84" />




> Created in Power BI, featuring:

- KPI cards (total orders, total revenue, average revenue)
- Revenue by city
- Revenue by Product
- order by manager
- Revenue by date



---
## Conclusion

> Overview

This Resturant sales Performance business demonstrates strong revenue performance but has opportunities to improve geographic expansion, product balac, and sales consistency.

> Key Findings

* High revenue despite moderate order volume
* Revenue is concentrated in specific cities
* Sales performance varies among managers
* Revenue tends show fluctutations across different period.
* Digital payment methods dominate customer preference.
* Certain cities and products dominate revenue contribution


> ## Recommendation

* Expand marketing in low-performing cities
* Promote underperforming products
* stregthen digital payment infrastructure
* Provide training for weaker managers
* Cross-selling of product under-performing



