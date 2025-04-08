# Atliq Hardware Business Insights

### Provide Insights to Management in Consumer Goods Domain



## Overview:
Atliq Hardware is a leading  computer hardware company in India with operations in other countries. They focus on making high-quality products but want to improve their use of data to make faster, smarter decisions.

## Table of Contents:

- [Problem Statement](#problem-statement)
- [Business Queries by Management](#Business-Queries-by-Management)
- [Results and Insights](#results-and-insights)
- [Tools & Technique used](#tools--technique)
- [Business Model](#business-model)
- [Data Source](#data-source)
- [Data Modeling](#data-modeling)
- [SQL Query](#sql-query)
  

## Problem Statement:
Atliq’s management noticed they lack the insights needed for quick decision-making. To fix this, they sent business Queries to their data analytics team.
The goal of this project is to provide clear and accurate insights for 10 specific business questions from the ad hoc requests. These insights will be used by Executive as top management to improve decision-making.

**Tasks**
- Run SQL queries to answer the 10 ad hoc business requests.
- Analyze the data and identify key insights that respond to the needs of the business.
- Create a presentation that clearly shows these insights in a way that top-level management can easily understand and use for decision-making.



## Business Queries by Management: 
1.  Provide the list of markets in which customer  "Atliq  Exclusive"  operates its business in the  APAC  region. 

2.  What is the percentage of unique product increase in 2021 vs. 2020? 
The final output contains these fields, 
unique_products_2020 
unique_products_2021 
percentage_chg.

3.  Provide a report with all the unique product counts for each  segment and sort them in descending order of product counts. 
The final output contains 2 fields -
segment 
product_count 

4.  Follow-up: Which segment had the most increase in unique products in 2021 vs 2020? 
The final output contains these fields - 
segment 
product_count_2020 
product_count_2021 
difference.

5.  Get the products that have the highest and lowest manufacturing costs. 
The final output should contain these fields -  
product_code 
product 
manufacturing_cost 

6.  Generate a report which contains the top 5 customers who received an average high  pre_invoice_discount_pct  for the  fiscal  year 2021  and in the Indian  market. 
The final output contains these fields -
customer_code 
customer 
average_discount_percentage 

7.  Get the complete report of the Gross sales amount for the customer  “Atliq Exclusive”  for each month  . This analysis helps to  get an idea of low and high-performing months and take strategic decisions. 
The final report contains these columns: 
Month 
Year 
Gross sales Amount 

8.  In which quarter of 2020, got the maximum total_sold_quantity? The final output contains these fields sorted by the total_sold_quantity, Quarter total_sold_quantity.

9.  Which channel helped to bring more gross sales in the fiscal year 2021 and the percentage of contribution? 
The final output  contains these fields - 
channel 
gross_sales_mln 
percentage 

10.  Get the Top 3 products in each division that have a high total_sold_quantity in the fiscal_year 2021? 
The final output contains these fields -  
division 
product_code 
codebasics.io 
product 
total_sold_quantity 
rank_order.


## Results and Insights:
Ths [Presentation](https://github.com/bhavik-singhi/Atliq-Hardware-Business-Insights/blob/main/Ad_Hoc%20Presentation%20.pdf) contains all the relevant insights and results.


## Tools & Technique:
- Data Analysis
   - Microsoft Excel
   - Microsoft Power BI Desktop
   - MS Powerpoint
   - Data Modeling
   - MySQL Workbench
   - SQL (CTE, Join, Sub Query, Window Function)

- Project Documentation
   - Git & Github
   - VS Code Editor

## Business Model:
Let's Explain how Atliq Hardware sell their products. 

<p align="center">
    <img src="https://raw.githubusercontent.com/PuranjoyPatra/Resume_Project_Challenge_4/refs/heads/master/images/business_model/BM-2.png" alt="Sell flow Overview" >
  </p>

  You can understand by this above image. Atliq first send their prroducts from their warehouse to different **Customers** who have partnered with Atliq then these customers sell Atliq's products to end user who consume the products. They are called **Consumer**.

  Atliq sell products through different Platforms and different Channels.

  <p align="center">
    <img src="https://raw.githubusercontent.com/PuranjoyPatra/Resume_Project_Challenge_4/refs/heads/master/images/business_model/BM-1.png" alt="Platform and Channel Overview" >
  </p>

  Through **Direct** channel, Atliq sell products diectly to the end user (Consumer).

  Atliq have different kinds of productline. Look at the below chart.

  <p align="center">
      <img src="https://raw.githubusercontent.com/PuranjoyPatra/Resume_Project_Challenge_4/refs/heads/master/images/business_model/BM-3.png" alt="Product Line Overview" >
    </p>

## Data Source:

A sql sump file is provided by Codebasics, which I have imported into MySQL Workbench and have got access the database named *_gdb023_* (atliq_hardware_db). It includes six main tables:

<p align="center"> Preview </p>


  <p align="center">
    <img src="https://raw.githubusercontent.com/PuranjoyPatra/Resume_Project_Challenge_4/refs/heads/master/images/DS-overview.png" alt="Dataset Overview" >
  </p>


> [!IMPORTANT]
> Data is available from Fiscal Year 2020 to 2021. At Atliq Hardware fiscal year starts from September month of calendar year (Look at below table for reference).

<p align="center">
    <img src="https://raw.githubusercontent.com/PuranjoyPatra/Resume_Project_Challenge_4/refs/heads/master/images/qtr-table.png" alt="Quarter Month Table" >
  </p>

## Data Modeling
Here you can check the Data Model which is used for this project. I have created this model in MySQL Workbench. 

<p align="center">
<img src="https://raw.githubusercontent.com/PuranjoyPatra/Resume_Project_Challenge_4/refs/heads/master/data_model/data-model-preview.png" alt="Data Model Preview" >

## SQL Query:
Check out all SQL Queries from [here](https://github.com/bhavik-singhi/Atliq-Hardware-Business-Insights/blob/main/SQL_Code.sql)
