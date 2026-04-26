# E-Commerce Sales Analysis (Online Retail Dataset)
Project Overview

This project analyzes real-world transactional data from an online retail store to uncover key business insights, customer behavior patterns, and sales trends. The goal is to demonstrate practical data analysis skills using Python, including data cleaning, exploratory analysis, and data visualization.

Objectives

* Clean and preprocess raw transactional data
* Analyze sales performance and revenue trends
* Identify top-selling products and high-value customers
* Understand geographic sales distribution
* Generate actionable business insights

Dataset

* Source: Kaggle (Online Retail Dataset)
* Records: ~500,000+ transactions
* Time Period: December 2010 – December 2011

Key Features:

* InvoiceNo – Transaction ID
* StockCode – Product Code
* Description – Product Name
* Quantity – Number of items purchased
* InvoiceDate – Date of transaction
* UnitPrice – Price per unit
* CustomerID – Unique customer identifier
* Country – Customer location

Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

Data Cleaning Steps

* Removed missing CustomerID values
* Filtered out cancelled transactions (InvoiceNo starting with 'C')
* Removed negative and zero quantities
* Converted InvoiceDate to datetime format
* Created a new feature: **TotalPrice = Quantity × UnitPrice**

Key Analysis & Visualizations

Top Selling Products

* Identified products with highest sales volume
* Visualized using bar charts

Revenue by Country

* Analyzed geographic contribution to total revenue
* Found dominant markets

Monthly Sales Trend

* Examined revenue patterns over time
* Identified seasonal trends

Top Customers

* Ranked customers based on total spending
* Highlighted high-value customers

Key Insights

* A small number of products generate the majority of sales
* The United Kingdom contributes the highest share of revenue
* Sales show seasonal peaks, especially during holiday periods
* A small segment of customers drives a large portion of total revenue

Business Recommendations

* Focus marketing on top-performing products
* Retarget high-value customers with loyalty programs
* Expand operations in high-revenue countries
* Plan inventory based on seasonal demand trends

