# SQL Data Analysis Project: Northwind Retail Dataset

# Overview
This project is an end-to-end **SQL and Excel data analysis case study** using the Northwind database, a standard retail dataset. It demonstrates how to extract, analyse, and present business insights using structured data. The project reflects real-world data analyst tasks, from querying databases to communicating insights through visualisations.


# Objectives
## The project aims to:
* Import Data into database and profile the Datasets
* Extract meaningful insights from a relational database (sqlite)
* Clean and validate data for accurate reporting
* Apply core SQL concepts to solve business problems
* Present findings using Excel visualisations


# Executive Summary
This analysis of the Northwind retail dataset provides key insights into customer behaviour, operational efficiency, and overall business performance.

The business demonstrates a **strong and active customer base**, with 830 total orders generating a revenue of **126,579.04**, indicating healthy commercial activity. However, performance is **not evenly distributed** across customers, products, or regions.

A small group of **high-value, repeat customers** drives a significant share of total orders, highlighting the importance of retention strategies. Similarly, **freight costs are concentrated among a few customers**, suggesting that a minority contributes heavily to shipping expenses, while most customers operate at lower cost levels.

Geographically, the customer base is **globally distributed but heavily concentrated in key markets**, particularly **Brazil, France, and Germany**, with Brazil emerging as the strongest growth opportunity. This uneven distribution highlights clear regions for expansion and strategic focus.

From a product perspective, inventory is **unevenly distributed across categories**, with certain categories dominating, indicating both **focused investment areas and potential gaps** for expansion or diversification.

Operationally, the business faces **data quality and process challenges**. Missing region data across multiple countries reveals a **systemic data management issue**, which could impact logistics and customer segmentation. In addition, **21 pending shipments** point to inefficiencies in the order fulfilment process that may affect customer satisfaction.

On the supply side, the company maintains a **diversified supplier base**, reducing dependency risks but potentially limiting opportunities for strategic supplier consolidation and cost optimisation.

Overall, the business is performing well but can unlock further value by improving **data quality, operational efficiency, customer retention strategies, and targeted market expansion**.


# Dataset
The dataset used is the **Northwind SQLite database**, downloaded from Kaggle, which contains retail business data across multiple tables, including:

* Customers
* Orders
* OrderDetails
* Products
* Suppliers
* Categories

[Northwind SQLite database](https://www.kaggle.com/datasets/munawarsaudagar/northwind-2000-sqlite?resource=download)

# Tools & Technologies

* SQL (SQLite Online)
* Excel (for analysis and visualisation)

# Project Workflow
## 1. Database Accessing
* Downloaded the Northwind `.sqlite` database from Kaggle
   
## 2. Data Loading
* Imported the Northwind `.sqlite` database into SQLite Online
* Profiled tables and relationships

## 3. SQL Analysis/Querying
* Wrote and executed queries to answer business-focused questions
* Applied concepts such as:

  * DISTINCT
  * NULL handling
  * Aggregate functions (SUM, COUNT, AVG)
  * GROUP BY
  * HAVING
  * Aliasing

## 4. Data Export
* Exported query results into Excel files

## 5. Visualisation
* Created visuals (bar, column, line) using Excel
* Added titles and structured sheets for clarity


# Key Business Questions Solved
1. List of unique countries where customers are located
2. All customers who do not have a region assigned
3. Total number of orders placed
4. Total revenue using the Order Details table
5. Total number of products in each category
6. Customers who have placed more than 10 orders
7. Average freight cost per customer
8. Suppliers who supply more than 5 products
9. Countries that have more than 5 customers
10. Total number of orders that have not been shipped yet


# Key Skills Demonstrated
* SQL querying and database interaction
* Data cleaning and validation
* Business-oriented data analysis
* Data aggregation and summarisation
* Insight generation and reporting
* Data visualisation and storytelling



# Key Insight
## Global distribution of Customer base 
👉 *“The customer base is globally distributed but heavily concentrated in Europe, indicating a strong core market with opportunities for geographic expansion.”*

* SQL QUERY
![image alt](banking_database_er_diagram.jpg)

* Result
![image alt](banking_database_er_diagram.jpg)

## Incomplete customer data 
👉 *“Customer data shows widespread missing region information across multiple countries, highlighting a systemic data quality issue that could impact operations and decision-making.”*

* SQL QUERY
![image alt](banking_database_er_diagram.jpg)

* Result
![image alt](banking_database_er_diagram.jpg)
![image alt](banking_database_er_diagram.jpg)

## Order Volume Overview 
👉 *“The company has handled 830 orders, reflecting strong customer activity and providing a solid foundation for deeper performance and revenue analysis.”*

* SQL QUERY
![image alt](banking_database_er_diagram.jpg)

* Result
![image alt](banking_database_er_diagram.jpg)

## Total revenue generated
👉 *“The business generated a total revenue of 126,579.04, highlighting overall performance while reflecting the impact of pricing and discount strategies.”*

* SQL QUERY
![image alt](banking_database_er_diagram.jpg)

* Result
![image alt](banking_database_er_diagram.jpg)

## Product Performance 
👉 *“Product distribution is uneven across categories, with a few categories dominating inventory, indicating focused investment areas and potential gaps for expansion.”*

* SQL QUERY
![image alt](banking_database_er_diagram.jpg)

* Result
![image alt](banking_database_er_diagram.jpg)
![image alt](banking_database_er_diagram.jpg)

## High-Value Customers 
👉 *“A small group of repeat customers drives a large share of orders, highlighting key accounts for retention and opportunities to increase order frequency among mid-tier customers.”*

* SQL QUERY
![image alt](banking_database_er_diagram.jpg)

* Result
![image alt](banking_database_er_diagram.jpg)
![image alt](banking_database_er_diagram.jpg)

## Average Order Value 
👉 *“Freight costs are unevenly distributed, with a small group of customers driving a large share of shipping expenses, while most customers maintain relatively low average costs.”*

* SQL QUERY
![image alt](banking_database_er_diagram.jpg)

* Result
![image alt](banking_database_er_diagram.jpg)
![image alt](banking_database_er_diagram.jpg)

## Suppliers with Multiple Products 
👉 *“No supplier dominates product supply, indicating a diversified supplier base with reduced risk but potential opportunities for strategic supplier consolidation.”*

* SQL QUERY
![image alt](banking_database_er_diagram.jpg)

* Result
![image alt](banking_database_er_diagram.jpg)

## Countries with High Customer Base 
👉 *“Customer distribution is concentrated in a few key markets, with Brazil leading, indicating strong expansion opportunities and clear priority regions for growth.”*

* SQL QUERY
![image alt](banking_database_er_diagram.jpg)

* Result
![image alt](banking_database_er_diagram.jpg)
![image alt](banking_database_er_diagram.jpg)

## Delayed or unshipped Orders
👉 *“21 pending shipments highlight potential fulfilment delays, signalling the need for improved operational efficiency and order tracking.”*


# Purpose
This project was developed to demonstrate **practical SQL and data analysis skills** required for entry-level data analyst roles. It showcases the ability to work with real datasets, generate insights, and present findings in a clear and structured manner.


# Author
##Kolawole Ilesanmi
Data Analyst | Business Intelligence Developer

