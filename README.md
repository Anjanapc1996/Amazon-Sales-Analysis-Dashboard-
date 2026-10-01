# Amazon-Sales-Analysis-Dashboard-PowerBI
## Project Overview
This project is an interactive amazon sales dashboard developed using Microsoft PowerBI.
It analyzes sales performance,Product and category performance,refional and customer informations and payment methods to identify impportant insights.
##Objectives
Build a 3-page Power BI dashboard on Amazon-style order data that lets a business user move from raw, messy transaction rows to a clean, trusted, interactive view of sales performance — without touching Excel formulas.
##Dataset
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
Promoted headers
-changed data types
-Trimmed and cleaned text values
-standardized region names
-removed duplicated records
-handled missing values
-recalculated sales using quantity*price
##Calculated columns
