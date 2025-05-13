Data_Analysis_Project - Sales and Order Management Analysis

This repository contains data analysis projects focused on exploring and analyzing datasets using tools like Excel, SQL, Power BI. The project includes data cleaning, data visualization, and insights generation to support data-driven decision-making.

Contents:
# Datasets (CSV/Excel files)
I have attached the CSV files of Sales data
**1. Pizza file:** containing record of pizza_id,pizza_type_id,size,price.
**2. Pizza Types:** containing record of pizza_type_id,name,category,ingredients.
**3. Orders:** containing record of order_id,date,time.
**4. Order details:** containing record of order_details_id,order_id,pizza_id,quantity.

# SQL Queries and Scripts
1..Import date to MYSQL workbench
--  Create a databse named data_analysis_project
Create database Data_Analysis_Project;

-- use teh database to upload the sales details available in CSV file
use Data_Analysis_Project;     

-- left click and Table data import wizard,browse the path for which files available,select file and click "next" ,select "Create new Table" if you want to continue with same data structres or else you create the new table 
example i have created my own datatypes and contraints 

Create table Orders(order_id int not null primary key,order_date date not null,order_time time not null);


# Visualizations (Power BI/Excel)
# Insights and Reports

Tools and Technologies:
1. SQL (MySQL)
2.Power BI / Tableau
3. Advanced Excel

