# Amazon-Sales-Analysis-Dashboard-PowerBI
📌 ##Project Overview

This project presents an interactive mazon sales dashboard developed using Microsoft PowerBI.

It analyzes sales performance,Product and category performance,refional and customer informations and payment methods to identify impportant insights.

🎯 ##Objectives
The main objectives of this project are:

-Analyze overall sales performance
-Identify top-performing product categories
-Compare sales across different outlet regions
-Analyze sales by location customer and order patterns
-Understand payment method usage
- Track monthly sales trends

##📂 Dataset
-amazon_sales_dashboard_data.csv  
-Records:6000 rows
-Period:jan 2023-dec 2024
-columns:10

##Main columns
-Order Id
-Order_Date
-Category
-Product_Name
-Quantity
-Price
-Sales
-Region
-Customer_Name
-Payment_Method

##Data cleaning
Data cleaning and trannformation were performed usig powerquery.
steps include:
-Promoted headers
-changed data types
-Trimmed and cleaned text values
-standardized region names
-removed duplicated records
-handled missing values
-recalculated sales using quantity*price

##Calculated columns
-Order month
-Order year
-Price tier
-Is Weekend order

##DAX Measures
-Total sales
-Total orders
-Units sold
-Avg order value
-Total customers
-Sales MOM% Change
-Top Category sales
-% of total sales

##Dashboard pages
1.Sales Overview
KPI
-Total sales
total orders
avg order value
total quantity
monthly sales trend 
sales by payment method
sales by region
2.Product and category analysis


