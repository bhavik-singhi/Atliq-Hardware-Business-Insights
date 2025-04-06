# Atliq Hardware Business Insights

### Provide Insights to Management in Consumer Goods Domain



## Overview:
Atliq Hardware is a leading  computer hardware company in India with operations in other countries. They focus on making high-quality products but want to improve their use of data to make faster, smarter decisions.

## Table of Contents:

- [Problem Statement](#problem-statement)
- [Tools & Technique used](#tools--technique)
- [Results and Insights](#Results and Insights)
- [Business Model](#business-model)
- [Task](#task)
- [Data Source](#data-source)
- [Data Modeling](#data-modeling)
- [Business Question (ad-hoc request)](#business-question-ad-hoc-request)
- [SQL Query](#sql-query)
  

## Problem Statement:
Atliq’s management noticed they lack the insights needed for quick decision-making. To fix this, they sent business Queries to their data analytics team.
The goal of this project is to provide clear and accurate insights for 10 specific business questions from the ad hoc requests. These insights will be used by Executive as top management to improve decision-making.

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

## Results and Insights:

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


## Goal:
The goal of this project is to provide clear and accurate insights for 10 specific 
business questions from the ad hoc requests. These insights will be used by Executive as
top management to improve decision-making.


## Task:
- Run SQL queries to answer the 10 ad hoc business requests.
- Analyze the data and identify key insights that respond to the needs of the business.
- Create a presentation that clearly shows these insights in a way that top-level management can easily understand and use for decision-making.

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


## Business Question (ad-hoc request):
There are 10 ad-hoc request on which I run SQL query to extract answers and then analyze it for getting key insights from that outputs.

You can see the ad-hoc requests [here](https://github.com/bhavik-singhi/Atliq-Hardware-Business-Insights/blob/main/Assets/Ad-hoc-requests.pdf)

## SQL Query:
Check out all SQL Queries from [here](https://github.com/bhavik-singhi/Atliq-Hardware-Business-Insights/blob/main/SQL_Code.sql)
