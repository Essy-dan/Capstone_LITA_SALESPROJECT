
Capstone Project Documentation with the Incubator's Hub.

### Project Overview
---
Businesses have always used data to make informed business decisions. With significant advancements in collecting, storing, analyzing, and reporting data in the last few decades, extracting actionable insights from large and complex datasets has never been easier, It has now become an indispensable tool for organizations seeking to gain a competitive edge. More than ever, organizations have now been able to drive informed decisions, optimize processes, and improve overall performance by leveraging analytics technology. Such organizations include large retail companies.
This project presents an exploratory data analysis (EDA) of E-commerce sales data for a retail company that closely resembles the operational characteristics of real-world retailers. The analysis aims to uncover valuable patterns, trends, and insights that will help the company better understand its sales dynamics, customer behavior, and profitability.

Project Summary
---

In this project, we are tasked with analyzing the sales performance of a retail store, to uncover key insights such as top-selling products, regional 
performance, and monthly sales trends.

### Goal
---

The goal is to produce an interactive Power BI dashboard that highlights the findings such as; top-selling products, regional 
performance, and monthly sales trends.

### Data Source
---
The primary source of data used here is Data Sale.csv and this is an open source data that can be freely downloaded from an open source online such as Kaggle or FRED or any other data repository site.

### Dataset Explanation
---
- Order ID: A unique identifier for each order placed. 
- Customer ID: A unique identifier assigned to each retailer in the dataset.
- Product: Represents the classification or grouping of products.
- Region: Refers to a specific geographical area or district where the sales activity or retail operations occur.
- Order Date: The date when a particular order or sales transaction took place.
- Quantity: The quantity or number of units of a particular product sold during a specific sales transaction.
- Unit Price: The cost or price associated with a single unit of a product.
- Total Sales: The overall revenue generated from the sales transactions

- ### Exploratory Data Analysis

EDA involved the exploration of the data to answer some questions about the Data such as:

Total Sales for each product category and What product is the highest selling?
what is the overall sales trend?
number of sales transaction in each region, and what region has the highest sales?
percentage of total sales by region?

### Tools Used
---
- Microsoft Excel for data cleaning and Analysis
- Structured Query Language- SQL for querying, storing, updating, and retrieving data.
- PowerBI for data visualization
-  Github for Portfolio building.

### Analysis Summary
---
The analysis was conducted using combination tools such as; Microsoft Excel, Structured Query Language -SQL, PowerBI following a series of steps outlined below:

1. Data Cleaning:
The initial dataset was assessed for consistency, reliability, completeness, duplicates, extra spaces, blanks, and correct spelling.
Verification checks were performed to ensure the dataset's integrity and cleanliness.
- Data Transformation:
The dataset was transformed to enhance its suitability for analysis.

2. Data Analysis:
- Excel's pivot table functionality was utilized to perform the analysis.
- Pivot table calculations and aggregations were employed to derive meaningful insights from the data.
- Various SQL queries were written to extract meaningful columns from dataset.
3.	Data Visualization:
- The analysis results were visualized using various Excel charts, including pivot table charts.
- Slicers were implemented to provide interactivity and enhance the dashboard's usability.
Overall, the Excel analysis and visualization process facilitated a thorough examination of the data, enabling the extraction of valuable insights and presenting them in an interactive and visually appealing manner.

### Busiess Task/Dashboard Component
---
The overall sales for 2024 up to August 2024 combined is #2,101,090.

The total units sold amount to 68,461 units.

The average price per unit sold is #29.
# Excel Summaries of Total Sales by Product, Region, and Month using Pivot Tables.








The pivot tables shows shoes as the highest selling product with total reveue of #613,380 and 29.19% of the total sales, and socks as the lowest purchased product with total revenue of #180,785 with 8.60% contribution to total sales value. The pivot tables also shows the region with most sales being South with total revenue of #927,820 with 44.16% to the total sales.

# SQL QUERIES

 1. retrieve the total sales for each product category
```
SELECT Product, SUM(Quantity*Unitprice) AS Total_Sales from [dbo].[SalesData] 
 GROUP BY product
```

 2. find the number of sales transactions in each region.
 
```
SELECT COUNT(ORDERID) AS Sales_Transaction, Region from [dbo].[SalesData] 
 GROUP BY Region
```

3. find the highest-selling product by total sales value.

```SELECT TOP 1 Product, SUM(Quantity*Unitprice) AS Total_Sales from [dbo].[SalesData] 
GROUP BY Product 
ORDER BY Total_Sales DESC
```

4. calculate total revenue per product.

```
SELECT Product, SUM(Quantity*Unitprice) AS Total_Sales from [dbo].[SalesData] 
GROUP BY Product
``` 

5.calculate monthly sales totals for the current year. done

 ```
SELECT
 MONTH(OrderDate) AS Month,
    SUM(Quantity*Unitprice) AS Monthly_TotalSales
FROM [dbo].[SalesData] 
WHERE YEAR(OrderDate) = YEAR(GETDATE()) 
 GROUP BY MONTH(OrderDate)
ORDER BY Month
```

 6.find the top 5 customers by total purchase amount.

```
SELECT TOP 5 CustomerID, SUM(Quantity*Unitprice) AS Total_Purchase_Amount FROM [dbo].[SalesData]
GROUP BY CustomerID
ORDER BY Total_Purchase_Amount DESC
```

7. calculate the percentage of total sales contributed by each region.

```
SELECT region, 
       SUM(quantity * unitprice) / (SELECT SUM(quantity * unitprice) FROM [dbo].[SalesData]) * 100 AS percentage_sales
FROM [dbo].[SalesData]
GROUP BY region
```

8. identify products with no sales in the last quarter.

```
SELECT DISTINCT Product FROM [dbo].[SalesData]
WHERE PRODUCT NOT IN (SELECT DISTINCT Product FROM [dbo].[SalesData]
WHERE OrderDate >= DATEADD(QUARTER, -1, GETDATE()))
```










```SQL
SELECT * FROM TABEL1
WHERE CONDITION = TRUE
```



