# Supply-Chain-Data-Analysis-Project


## Overview
This project analyzes a real-world Supply Chain dataset from Kaggle, originally provided by DataCo Global. The objective is to gain insights into customer behavior, product performance, shipping efficiency, and overall sales trends using SQL and Tableau.

## Tools & Technologies
- SQL (MySQL): Data transformation, cleaning, and analysis
- Excel:  Initial data wrangling and structuring
- Tableau: Interactive dashboards and visualizations

## Dataset
- Source: Kaggle - Supply Chain Dataset
- Provider: DataCo Global
- Original Format: A single Excel file with mixed information
- Tables Created:
  - Customer
  - Order
  - Product
  - Shipping

## Preprocessing
- Split original Excel into multiple logical files
- Removed unnecessary columns (e.g., zipcode, product_image, product_description)
- Created a relational schema with appropriate primary keys
- Built an Entity-Relationship Diagram (ERD)

## ER Diagram
Entity-relationship diagram illustrating data model relationships among the tables (Customer, Order, Product, Shipping

## SQL Analysis
Performed advanced querying and transformation to extract insights:

### Key Techniques:
- Joins, CTEs, Subqueries
- Window Functions: RANK, DENSE_RANK, ROW_NUMBER, SUM, AVG
- String & Date Functions: CONCAT, MONTH(), YEAR()
- Conditional Logic: CASE WHEN
- Filtering & Aggregation

### Analysis Performed:
- Count of distinct customers, cities, states, zip codes, and countries
- Top 10 cities with the most customers
- Customer segment and department distributions
- Total sales by region
- Top 10 products by revenue
- Average delivery days by shipping mode
- Late deliveries by region
- Top 10 customers by profit
- Revenue by product category
- Order status distribution
- Shipping performance: Actual vs Scheduled
- Monthly and yearly sales trends
- Late delivery percentage by shipping mode
- Most profitable product
- Late vs on-time shipments
- Top 3 product categories by sales per region

## Tableau 
Built an interactive dashboard highlighting KPIs and visual trends:

- Key Metrics (KPI Cards):
  - Total Customers
  - Total Products
  - Total Sales
  - Number of Product Categories
  - Average Delivery Delay (in days)
- Visuals:
  - Profit by State — Tree Map
  - Top 10 Products by Revenue — Bar Chart
  - Shipping Mode Distribution — Pie Chart
  - Customer Segment Distribution — Bar Chart

Acknowledgment
- Dataset from Kaggle: DataCo Supply Chain Dataset
- Dataset name: DataCo SMART SUPPLY CHAIN FOR BIG DATA ANALYSIS






