# Insights Developer Role challenge
Created By:   Ravinendra Pratap

Created on:   28-Jul-2024

# Data Analysis Task

## Objective
To assess your SQL skills, data pipeline-building capabilities, and BI visualization expertise using a provided sales dataset.

## Dataset
You will be provided with a CSV file containing sales transaction data with the following columns:
- TransactionID
- Date
- CustomerID
- ProductID
- Quantity
- Price
- Discount
- TotalAmount
- StoreID
- Region
- SalespersonID

## Part 1: SQL Skills
Perform the following tasks using SQL:
1. Extract all sales data for the last quarter.
2. Calculate the total sales amount per region.
3. Join the sales data with a customer details table to find the total sales amount per customer.
4. Retrieve the top 10 products by sales amount in the last month.
5. Identify customers who have not made a purchase in the last six months using a subquery.

## Part 2: Pipeline Building
Build an ETL pipeline to automate the processing of the sales dataset:
1. Write a script to import the dataset from a CSV file into a database.
2. Apply necessary transformations, such as calculating the TotalAmount.
3. Load the transformed data into a target database or data warehouse.

## Part 3: BI Visualization
Using a BI tool of your choice (e.g., Tableau, Power BI), create the following visualizations:
1. A dashboard showing total sales, sales trends over time, and sales breakdown by region.
2. Visualize the top 10 customers by sales and the distribution of sales among different customer segments.
3. Create a visualization to show the best-selling products and products with the highest discounts.

## Submission
Submit your SQL queries, the ETL script, and screenshots or a link to your BI dashboard.

## Steps to Create the Task

1. **Provided CSV Dataset**

Sales Transactions Dataset properties:
* 100 records
* Date Period: 03/01/2023 to 31/12/2023
* Format: csv format
* File size ~ 6KB
  
Field descriptions
   - **TransactionID**: Unique identifier for each transaction.
   - **Date**: The date when the transaction occurred.
   - **CustomerID**: Unique identifier for the customer.
   - **ProductID**: Unique identifier for the product.
   - **Quantity**: Number of items purchased.
   - **Price**: Price per item.
   - **Discount**: Discount applied to the transaction.
   - **TotalAmount**: Total amount after discount.
   - **StoreID**: Unique identifier for the store.
   - **Region**: Geographic region of the store.(East, North, South, West)
   - **SalespersonID**: Unique identifier for the salesperson.

2. **SQL Skills Assessment**
   
   Prepare a set of SQL tasks that needs to perform on the dataset.

   These tasks can include:
   - **Data Extraction**: Write a query to extract all sales data for the last quarter.
   - **Aggregation**: Calculate the total sales amount per region.
   - **Joins**: Find the total sales amount per customer, considering a separate customer details table.
   - **Filtering and Sorting**: Retrieve the top 10 products by sales amount in the last month.
   - **Subqueries**: Identify customers who have not made a purchase in the last six months.

4. **Pipeline Building Skills**

   Build a data pipeline that automates the process of data extraction, transformation, and loading (ETL).

   This could involve:
   - **Data Ingestion**: Write a script to import the dataset from a CSV file into a database.
   - **Data Transformation**: Apply necessary transformations, such as calculating the TotalAmount as Quantity * Price - Discount.
   - **Data Loading**: Load the transformed data into a target database or a data warehouse.

6. **BI Visualization Skills**

   Using BI tool (e.g., Tableau, Power BI) to create several visualizations:
   - **Sales Dashboard**: Create a dashboard showing total sales, sales trends over time, and sales breakdown by region.
   - **Customer Insights**: Visualize the top 10 customers by sales and the distribution of sales among different customer segments.
   - **Product Performance**: Create a visualization to show the best-selling products and products with the highest discounts.

This task covers SQL, pipeline building, and BI visualization skills comprehensively, giving you a clear view of the candidate’s capabilities in each area.
