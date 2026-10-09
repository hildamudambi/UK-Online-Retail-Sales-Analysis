# UK-Online-Retail-Sales-Analysis
A Power BI project analyzing UK online retail sales data, from data cleaning to dashboard insights.

## Project Overview

This project analyzes sales data from a UK-based online retail business covering December 2010 to December 2011.

I used Power Query to clean and prepare the data, then Power BI to analyze sales performance and create an interactive dashboard. The dashboard explores revenue trends, country performance, and top-performing products to answer key business questions and generate insights and recommendations.
## Project Objectives

The objectives of this project were to:

* Evaluate overall sales performance using key sales metrics.
* Analyze monthly revenue trends.
* Identify the countries generating the most revenue and selling the highest quantities.
* Identify the top-performing products by revenue.
* Develop insights and recommendations to support business decision-making.
## Business Problem

The company has a large volume of online retail transaction data, but without proper analysis, it can be difficult to understand its sales performance, revenue patterns, market performance, and product contribution.

The business therefore needed to transform its raw transaction data into meaningful information that could help management identify sales trends, understand the strongest markets, evaluate product performance, and make informed decisions to support future growth.

## Key Business Questions

The analysis was guided by the following key business questions:

1. How is the business performing overall?
2. How does revenue change from month to month?
3. Which countries generate the most revenue?
4. Which countries have the highest quantity of products sold?
5. Which products generate the most revenue?

 ## Data Source & Dataset Description

The dataset was obtained from the **UCI Machine Learning Repository**. It contains transaction data from a UK-based online retail business covering **December 2010 to December 2011**.

The original dataset contained **541,909 rows and 8 columns**. Key fields include:

* **InvoiceNo:** Transaction or invoice number.
* **StockCode:** Product identification code.
* **Description:** Product description.
* **Quantity:** Number of units purchased.
* **InvoiceDate:** Date and time of the transaction.
* **UnitPrice:** Price charged per unit.
* **CustomerID:** Customer identification number.
* **Country:** Customer's country.


## Data Cleaning & Preparation

I used **Power Query** to clean and prepare the raw transaction data before analyzing it in Power BI.

The main data preparation steps included:

* Identifying and removing cancellation transactions.
* Removing records with negative quantities.
* Removing duplicate transaction records.
* Removing records with missing product descriptions or unit prices.
* Removing records with negative unit prices.
* Investigating and retaining records with zero unit prices.
* Replacing missing CustomerID values with **"Unknown"** so those records could remain in the analysis.

After cleaning, the prepared dataset was used for the sales analysis and interactive Power BI dashboard.

## Analysis & Calculations

After cleaning the dataset in Power Query, I loaded the prepared data into **Power BI** for analysis. I created calculated columns and measures to evaluate sales performance and answer the key business questions.

The main calculations included:

* **Sales Value:** Calculated using quantity multiplied by unit price.
* **Total Revenue:** The total revenue generated from sales.
* **Average Sales Value:** The average value per sales line.
* **Count of Orders:** The number of distinct orders.
* **Average Amount per Order:** The average revenue generated per order.
* **Total Quantity:** The total number of products sold.

I also created Year, Month, and Month Number columns to analyze revenue trends over time and display months in chronological order.

## Power BI Dashboard

I developed an interactive **Power BI dashboard** to present the results of the sales analysis.

The dashboard includes key performance indicators for Total Revenue, Total Quantity, Average Sales Value, Average Amount per Order, and Count of Orders. The **Country** and **Month** slicers allow users to explore the results using different filters.

The visualizations show:

* Top 20 countries by revenue.
* Top 20 countries by quantity sold.
* Top 10 products by revenue.
* Revenue by month.

The dashboard provides a clear overview of sales performance and helps identify patterns across countries, products, and months.










