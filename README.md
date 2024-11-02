
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
- The analysis results were visualized using PowerBI.
- Slicers were implemented to provide interactivity and enhance the dashboard's usability.
Overall, the analysis and visualization process facilitated a thorough examination of the data, enabling the extraction of valuable insights and presenting them in an interactive and visually appealing manner.

### Busiess Task/Dashboard Component
---
The overall sales for 2024 up to August 2024 combined is #2,101,090.

The total units sold amount to 68,461 units.

The average price per unit sold is #29.
# Excel Summaries of Total Sales by Product, Region, and Month using Pivot Tables.

![Screenshot (178)](https://github.com/user-attachments/assets/444beae1-a476-424a-b49b-cddbe75df890)

![Screenshot (180)](https://github.com/user-attachments/assets/36ae76b2-96e7-4632-8b23-13d9446caad0)



The pivot tables shows shoes as the highest selling product with total reveue of #613,380 and 29.19% of the total sales, and socks as the lowest purchased product with total revenue of #180,785 with 8.60% contribution to total sales value. The pivot tables also shows the region with most sales being South with total revenue of #927,820 with 44.16% to the total sales.

# SQL QUERIES

 1. retrieve the total sales for each product category
```
SELECT Product, SUM(Quantity*Unitprice) AS Total_Sales from [dbo].[SalesData] 
 GROUP BY product

![Screenshot (184)](https://github.com/user-attachments/assets/62fe34db-536c-419f-81cf-9e18fb927b1d)
```

 2. find the number of sales transactions in each region.
  
 ```
SELECT COUNT(ORDERID) AS Sales_Transaction, Region from [dbo].[SalesData] 
 GROUP BY Region
```
![Screenshot (181)](https://github.com/user-attachments/assets/5ae23098-fa19-4196-bff2-5a46ebe55164)

3. find the highest-selling product by total sales value.
```SELECT TOP 1 Product, SUM(Quantity*Unitprice) AS Total_Sales from [dbo].[SalesData] 
GROUP BY Product 
ORDER BY Total_Sales DESC
```
![Screenshot (186)](https://github.com/user-attachments/assets/bfdf78ac-6c73-483a-adb3-55a494931df5)

4. calculate total revenue per product.
```
SELECT Product, SUM(Quantity*Unitprice) AS Total_Sales from [dbo].[SalesData] 
GROUP BY Product
``` 
![Screenshot (187)](https://github.com/user-attachments/assets/d370ebba-e983-4383-9df9-e2fb9301fc34)

5.calculate monthly sales totals for the current year. 
 ```
SELECT
 MONTH(OrderDate) AS Month,
    SUM(Quantity*Unitprice) AS Monthly_TotalSales
FROM [dbo].[SalesData] 
WHERE YEAR(OrderDate) = YEAR(GETDATE()) 
 GROUP BY MONTH(OrderDate)
ORDER BY Month
```
![Screenshot (188)](https://github.com/user-attachments/assets/a65f5284-2902-46f6-8c7a-20a329e85444)

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
![Screenshot (191)](https://github.com/user-attachments/assets/17e5b5f2-1380-400a-938e-6fba70411218)

8. identify products with no sales in the last quarter.
```
SELECT DISTINCT Product FROM [dbo].[SalesData]
WHERE PRODUCT NOT IN (SELECT DISTINCT Product FROM [dbo].[SalesData]
WHERE OrderDate >= DATEADD(QUARTER, -1, GETDATE()))
```
![Screenshot (190)](https://github.com/user-attachments/assets/92df6a5a-ac07-4e2c-abe4-d57f541e9a61)






Inference
Sales Overview: It was discovered that the sales decline in Year 2024 with N109,570 lower than the revenue for the year 2023. In the last quarter of 2023, 3 products out of 6 were not purchased by the customers, these products include; Shirt, Hat an Shoes. Also in the last quarter in the year 2024, only hat and shoes were sold leaving Jacket, Shirt, Gloves and socks unsold. There are many factors that might have caused the decline in revenue, it can be that there was a change in customer taste, rise in competition and this has to be addressed by having sales promotion and avertisement to increase the revenue.

Top performing products: By using the exel & SQL, the product "Shoes" was considered to be the top performing product base on the total revenue it generated which is higher than the other products.

Regional Breakdown:

East: In Year 2023, the total revenue generated was N393,945. However, there was a significant decline in 2024 with the total revenue coming down to N91,980 representing 62% decrease. This decrease in revenue may suggest increase in competitors, difficulty in maintaining sales, economic conditions and/or market contraction. This indicate a potential area of concern which requires immediate attention. The company should attempt to increase sales & marketing techniques, reaching more customers, maintaining good relationship with the current and new customers, create special incentives, develop a public reputation for quality and expertise, offer discount, rebates and coupons, review the current prices of products among others.
North: There was a notable increase in the total turnover from N143,960 in Year 2023 to N243,040 in Year 2024 with 26% increase. The company should invest more products in this region to better boost the total revenue.
South: This region also performs well in generating revenue to the company. However, there was a slight decrease in revenue generated as decrease of N33,820 was recorded representing 4% decrease. This is not a major challenge but the reason for the drop in revenue have to be investigate so as to maintan/increase the revenue in a subsequent year.
West: There is a significant increase in the revenue recorded in this region as N127,135 increase was recorded in between 2023 & 2024. It might be that the company is a monopoly. This need to be maintain for the region to keep on recording increase in revenue.
Conclusion
Based on the data sets analyzed for year 2023 and 2024, it was confirmed that the company recorded a declined revenue generation in South and most importantly East which raised a great concern. The company is advised to do a market survey so as to understand the customers' preference, improve/maintain the product quality and make a strategy plan on how to deliver and capture the heart of the customers. The company is also expected to maintain good relationship with the customers in the remaining region that recorded increase in revenue which are North and West as this will help to keep on recording increased revenue in future years.


```SQL
SELECT * FROM TABEL1
WHERE CONDITION = TRUE
```



