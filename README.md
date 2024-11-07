
**Sales Data Analysis**
[Project Overview](#project-overview)

[Objectives](#objectives)

[Expected Outcomes](#expected-outcomes)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Tools Used](#tools-used)

[Analysis](#analysis)

[Business Task/Dashboard Component](#business-task/dashboard-component)

[Key Strategies and Recommendations](#Key-strategies-and-recommendations)

[Conclusion](#conclusions)

### Project Overview
---

This project focuses on analyzing sales data for a retail business offering a range of products, including shoes, jackets,shirts,hats, gloves and socks. The primary goal is to uncover key sales trends, identify top-performing products, and analyze regional sales distribution to better understand customer preferences and maximize revenue potential. By examining this data, we aim to support strategic decision-making around inventory, pricing, and marketing efforts to drive growth and improve profitability.

### Objectives
---

1. Understand Product Performance:

Calculate average sales per product to determine which items are most popular and have the highest sales potential.

Identify top-selling products to spotlight high-demand items, which can guide inventory restocking and promotional strategies.

Examine product categories to see which categories (e.g., footwear, outerwear, accessories) are contributing the most to total sales.

2. Analyze Regional Sales Distribution:

Calculate total revenue by region to assess which regions are generating the most revenue and where there may be untapped potential.

Map sales distribution geographically to understand region-specific demand and optimize regional sales strategies.

3. Seasonality and Trends:

Analyze sales trends over time (e.g., monthly or quarterly) to identify any seasonal peaks or periods of increased sales activity.

Evaluate if certain products, such as jackets or hats, exhibit seasonal trends to aid in effective inventory planning.

4. Customer Insights:

Use data insights to understand customer buying patterns and preferences, which can help tailor marketing efforts to target specific demographics or regions more effectively.

### Expected Outcomes
---

Through this analysis, the project seeks to deliver actionable insights that will help:

Optimize Product Line and Stocking: By identifying best-selling products and average sales across categories, we can make informed decisions on which items to stock more frequently and where to introduce new offerings.

Targeted Marketing Campaigns: Insights on regional performance and seasonality will support the creation of tailored marketing campaigns that align with customer preferences, driving engagement and sales.

Enhanced Profitability: With data-driven strategies focused on high-demand products and key sales regions, the company can improve profitability by aligning inventory and marketing to meet customer demand efficiently.

### Data Source
---
The primary source of data used here is Data Sale.csv and this is an open source data that can be freely downloaded from an open source online such as Kaggle or FRED or any other data repository site.

### Dataset Explanation
---

![Screenshot (241)](https://github.com/user-attachments/assets/02a38b95-e087-4f5e-bb52-c210157e1156)

- Order ID: A unique identifier for each order placed. 
- Customer ID: A unique identifier assigned to each retailer in the dataset.
- Product: Represents the classification or grouping of products.
- Region: Refers to a specific geographical area or district where the sales activity or retail operations occur.
- Order Date: The date when a particular order or sales transaction took place.
- Quantity: The quantity or number of units of a particular product sold during a specific sales transaction.
- Unit Price: The cost or price associated with a single unit of a product.
- Total Sales: The overall revenue generated from the sales transactions

- ### Exploratory Data Analysis
- ---

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

### Analysis 
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

### Business Task/Dashboard Component
---
**Average Sales Per Product and Average Revenue By Region**

![Screenshot (285)](https://github.com/user-attachments/assets/fba62b05-3ead-43be-bf7e-d61580c935fb)

The table above shows the Average Sales per Product and Total Revenue by Region, providing valuable insights into sales performance across different products and regions.

- Average Sales per Product: This metric gives an overview of how each product is performing on average in terms of sales volume or revenue. It helps identify the top-performing products (such as shoes, jackets, or hats) that are driving the most sales and those that might need further marketing or promotion efforts. This analysis allows businesses to make informed decisions about inventory management, product strategy, and pricing adjustments.

- Total Revenue by Region: The total revenue breakdown by region helps to assess the geographical distribution of sales. By analyzing revenue across regions, businesses can pinpoint high-performing areas and regions with untapped potential. This data is essential for regional marketing strategies, sales planning, and decisions on resource allocation. Regions with the highest sales, like the South, may indicate opportunities for further investment or expansion, while underperforming regions can be targeted with tailored promotions or product offerings.

Together, these metrics provide a clear picture of product performance and regional sales trends, enabling strategic decisions to maximize revenue and improve business operations.


# Excel Summaries of Total Sales by Product, Region, and Month using Pivot Tables.

![Screenshot (238)](https://github.com/user-attachments/assets/74693a2b-3e97-4f1d-a0ad-5d7c44d6f9fd)


**Top Performer**

 Shoes stand out as the clear market leader, generating $613,330 in revenue, which significantly outpaces the other categories. This indicates a strong demand for shoes and possibly an opportunity to continue investing in or expanding this category. Shoes alone contribute ~29% of total revenue—a substantial portion of the business.
Shirts are also a high-performing category with $485,600 in revenue, contributing ~23% of total sales. Together, shoes and shirts make up over half of the total revenue, suggesting that the company’s strongest products are likely tied to these two items.
 
 **Mid-Performing Categories**

Hats and Gloves are the next top performers, with revenue contributions of $316,195 and $296,900, respectively. These categories hold an important mid-tier position in sales, together contributing ~29% of total revenue. This suggests that while these products do not lead in sales, they are still valuable and can be essential in diversifying the product range, attracting customers who may prefer a wider selection.

**Underperforming Products**

Jackets and Socks lag behind in revenue, with $208,300 and $180,785 respectively. Socks contribute only ~8.6%, while jackets contribute ~9.9% to total sales, highlighting them as lower-priority products in the current lineup. This lower contribution may indicate an opportunity to consider alternate strategies, such as promotions, bundling, or product redesign, to boost their sales—or possibly to reduce inventory focus if these products do not align well with the customer base.

![Screenshot (239)](https://github.com/user-attachments/assets/9589ccae-683b-43d8-b058-e366172bec96)

**Strong Sales Performance in the South Region**

Insight: The South region generated the highest revenue, nearly double that of other regions, contributing significantly to the company's total revenue. With $927,820 in total, the South’s sales stand out as a major source of revenue across both 2023 and 2024.

**Recommendation:** The business should consider identifying factors contributing to the South's success. For example, analyzing product popularity, customer preferences, and marketing efforts in this region could reveal patterns that can be replicated in other regions to drive sales growth.

**Growth Potential in the East and North Regions**

Insight: The East and North regions, though contributing to revenue, show lower performance compared to the South. For instance, the East has a total revenue of $485,925, and the North, $387,000, with only an 18-23% contribution to the overall revenue.

**Recommendation:** These regions have potential for growth, especially since the South’s performance demonstrates that the market potential is strong. The business could consider increasing marketing efforts, expanding product lines, or creating localized promotions tailored to customer needs in the East and North to stimulate sales. Additionally, deeper analysis into customer feedback and preferences in these areas could reveal opportunities for product or service adjustments that may better resonate with local customers.

**Trend in Revenue Contribution over Time (2023 vs. 2024)**

Insight: There’s an uneven growth pattern across the regions from 2023 to 2024. For example, the North region saw a significant increase in revenue from $143,960 in 2023 to $243,040 in 2024, while the South maintained a relatively consistent revenue between the two years.

**Recommendation:** The company could leverage the growth trend in the North by prioritizing resources there for 2024, such as enhancing supply chain logistics or increasing the sales team’s presence. Maintaining the South’s revenue levels also suggests strong market saturation or demand consistency, so expanding product options or introducing premium offerings in the South might maximize sales without eroding the existing customer base.

**Focus on Regional Marketing and Inventory Optimization**

Insight: Each region’s contribution highlights the need for tailored marketing strategies. The South’s high revenue suggests a strong customer base that could benefit from more targeted promotions, loyalty programs, or exclusive offers.

**Recommendation:** Tailoring marketing campaigns to target specific customer preferences in each region will likely yield higher returns. Additionally, optimizing inventory levels based on the demand in each region can help avoid overstocking or stockouts, reducing costs while ensuring product availability in high-demand areas like the South

**Top-Selling Products by Region**

South: Shoes are consistently the highest-selling product here, contributing significantly to total revenue. This indicates a strong preference for shoes in this region, making it a key product to continue promoting or investing in here.

East: Shirts lead in sales, with jackets, hats, and shoes following. Unlike the South, shoes perform poorly in the East. This suggests regional differences in product demand, possibly influenced by local preferences, seasonality, or demographics.

North: Shirts are also dominant, indicating they have broader appeal across multiple regions. However, the North’s overall revenue is less compared to other regions, showing potential for growth with targeted promotions.

West: Hats and gloves have strong sales, with hats leading the region. This suggests that products related to accessories might have unique appeal here, and emphasizing accessories could further boost sales.

![Screenshot (240)](https://github.com/user-attachments/assets/c79fc12a-d4df-4914-9da4-1bee1ea1bbfb)

![Screenshot (236)](https://github.com/user-attachments/assets/20746f26-bbf6-449f-814d-81800612253d)

The monthly revenue trends for 2023 and 2024 reveal some interesting insights about seasonality, possible shifts in demand, and market factors affecting sales performance. Here are some observations and possible explanations for the changes between the years:

- Overall Comparison Between 2023 and 2024 Revenue

In 2023, total revenue reached $1,105,330, while in 2024, $995,760 was generated by the reported months. This represents a drop in total revenue, which could signal shifts in customer demand, market conditions, or internal changes (e.g., pricing adjustments or inventory limitations).

January through August of 2024 shows increased revenue compared to the same period in 2023, but July 2024 saw a significant decline, which could indicate a one-off event or seasonal fluctuation

- Month-by-Month Analysis and Key Changes

January: Revenue surged in 2024 to $198,400 from $49,600 in 2023. This large increase could be due to a new promotion, product release, or seasonally strong demand (e.g., post-holiday shopping or New Year sales). The business might consider making January a focus period for sales efforts moving forward.

February and March: Both months show moderate growth in 2024, which could be a continuation of a successful early-year strategy, suggesting that products or campaigns introduced at the start of the year were well-received.

April: Revenue jumped from $7,425 in 2023 to $39,440 in 2024, indicating April may have become a stronger sales period, possibly due to a seasonal promotion or increased demand in spring. This month could be an opportunity to further build momentum with targeted campaigns.

June and August: These months in 2024 saw higher sales than in 2023 (e.g., $148,200 vs. $99,400 in June; $174,300 vs. $29,880 in August). This growth could reflect effective mid-year marketing efforts or a peak in seasonal demand. August’s large increase may indicate this month has grown in importance, perhaps due to back-to-school shopping or end-of-summer promotions.

July: In contrast, July 2024 saw a dramatic decline to $37,200 from $237,600 in 2023. This could be due to various factors, such as market shifts, decreased demand, or competition. Examining inventory, pricing, and competition in this month could reveal factors affecting this drop.

- Trends and Seasonal Insights

First Quarter (January to March): Sales were significantly higher in 2024, suggesting stronger early-year performance. This could be strategic for the business to capitalize on, with increased focus on marketing, discounts, or product launches at the start of the year.

Summer Months (June, July, August): The fluctuation between these months suggests that demand can be unpredictable. While June and August were strong in 2024, July dropped drastically, implying that sales in these months may be sensitive to external factors (e.g., travel season, holidays).

Quarter 4 Trends: Since October to December data is incomplete for 2024, it’s challenging to make a year-over-year comparison for late-year performance. However, in 2023, October and November were among the highest revenue months, indicating potential for a similar pattern in Q4 2024.

# SQL QUERIES

 1. retrieve the total sales for each product category
```
SELECT Product, SUM(Quantity*Unitprice) AS Total_Sales from [dbo].[SalesData] 
 GROUP BY product
```

![Screenshot (184)](https://github.com/user-attachments/assets/62fe34db-536c-419f-81cf-9e18fb927b1d)

Explanation:

1. Purpose:

This query calculates the total sales for each product category in the dataset. It provides insights into the revenue contribution of each category, helping identify the top-performing categories.

2. Breakdown:

SUM(Quantity*Unitprice): Calculates the total sales for each category by summing up sales values in the Total_Sales column.

GROUP BY ProductCategory: Groups the sales data by each unique product category, so that total sales are calculated per category.

ORDER BY Total_Sales DESC: Sorts the results in descending order based on total sales, allowing us to see the highest-performing categories at the top.

3. Insight Derived:

The output helps us understand which product categories (e.g., Shoes, Jackets, Hats) are generating the most revenue. This insight can guide decisions on inventory stocking, marketing efforts, and product development focus.

4. Potential Next Steps:

Analyze trends within these top categories over time to identify seasonality.

Compare these categories across regions to determine if certain products perform better in specific areas.

2. find the number of sales transactions in each region.
  
 ```
SELECT COUNT(*) AS Sales_Transaction, Region from [dbo].[SalesData] 
 GROUP BY Region
```
![Screenshot (181)](https://github.com/user-attachments/assets/5ae23098-fa19-4196-bff2-5a46ebe55164)

Explanation:

1. Purpose:

This query counts the total number of sales transactions in each region. The goal is to identify which regions have the highest and lowest transaction volumes. Understanding regional transaction counts helps us analyze customer engagement across different geographic locations.

2. Breakdown:

COUNT(*): Counts each sales record as one transaction, providing the total number of transactions for each region.

GROUP BY Region: Groups transactions by region, so that transaction counts are calculated for each unique region.

ORDER BY Total_Transactions DESC: Orders the results by transaction count in descending order, allowing us to quickly see the regions with the most transactions at the top.

3. Insight Derived:

This output helps us see which regions have the most sales activity, providing insight into customer demand and engagement patterns by location. For example, regions with high transaction volumes may indicate a strong customer base, while low-volume regions could present opportunities for growth or may need targeted marketing efforts.

4. Relevance to the Dataset and Project:

This analysis complements other metrics in the project, such as total revenue by region and average sales per product. Together, these metrics provide a holistic view of the business’s performance across regions, helping us understand where the company has the greatest sales potential. This insight can guide inventory allocation, regional sales strategies, and marketing investments to align with areas of high demand.

5. Potential Next Steps:

Further analyze the top regions to see which products are most popular in each area.

Compare transaction counts with revenue figures to assess whether high transaction volumes also translate to high sales revenue.

Investigate regional trends over time to understand if certain periods have higher transaction volumes in specific regions, which could support seasonal marketing or inventory planning.

3. find the highest-selling product by total sales value.

```SELECT TOP 1 Product, SUM(Quantity*Unitprice) AS Total_Sales from [dbo].[SalesData] 
GROUP BY Product 
ORDER BY Total_Sales DESC
```
![Screenshot (186)](https://github.com/user-attachments/assets/bfdf78ac-6c73-483a-adb3-55a494931df5)

Explanation:

1. Purpose:

This query identifies the highest-selling product by total sales value across all transactions. The goal is to pinpoint the product that has generated the most revenue, which can help focus efforts on products that drive the most business impact.

2. Breakdown:

SUM(Quantity*Unitprice): Calculates the total sales value for each product by summing up the sales amounts in the TotalSales column.

GROUP BY Product: Groups the data by each unique product, so the total sales are calculated individually for each product.

ORDER BY TotalSalesValue DESC: Sorts the results in descending order based on total sales value, ensuring the highest sales value appears at the top.

TOP 1: Returns only the top result, which is the product with the highest total sales value.

3. Insight Derived:

This result reveals which product has contributed the most to overall revenue, identifying a high-impact item that is driving sales. Knowing the highest-selling product allows the business to prioritize this product in marketing, ensure optimal stock levels, and potentially use it as a lead product to attract more customers.

4. Relevance to the Dataset and Project:

This query is key to understanding product performance within the dataset. By finding the top revenue-generating product, we gain insight into customer preferences and can see which products resonate most with the target market. This aligns with the project's goal of maximizing revenue by focusing on top-performing items and helps in strategic planning for product development and promotions.

Additionally, this metric complements other data points, such as average sales per product and total transactions by region, which together offer a comprehensive view of sales dynamics by product and geography.

4. calculate total revenue per product.
```
SELECT Product, SUM(Quantity*Unitprice) AS Total_Sales from [dbo].[SalesData] 
GROUP BY Product
``` 
![Screenshot (187)](https://github.com/user-attachments/assets/d370ebba-e983-4383-9df9-e2fb9301fc34)

Explanation:

1. Purpose:

This query calculates the total revenue generated by each product. By summing up sales values for each product, we can understand which products contribute most to the company’s revenue. This insight is crucial for identifying high-value products and helps in prioritizing these products in terms of marketing, production, and stocking.

2. Breakdown:

SUM(Quantity*Unitprice): Adds up the sales value for each transaction related to a specific product, giving the total revenue per product.

GROUP BY Product: Groups the results by each unique product, so that revenue calculations are conducted separately for each product.

ORDER BY TotalRevenue DESC: Sorts the results in descending order of revenue, allowing us to see the highest-earning products at the top.

3. Insight Derived:

This result shows which products generate the most revenue, helping the business focus on its most profitable products. For instance, shoes generate the highest revenue, the business might decide to increase stock or create special promotions around shoes to maximize sales further.

4. Relevance to the Dataset and Project:

This query directly relates to the project's goal of understanding product performance. By identifying revenue by product, the project can reveal which items are the most financially impactful and indicate where to focus future investment and marketing resources.

This analysis complements other queries, such as highest-selling product by total sales and transaction count by region, helping build a broader picture of which products perform best across different dimensions (e.g., sales volume vs. revenue contribution).

5. Potential Next Steps:

Examine top products across different regions to see if they are universally popular or only in specific areas.

Track revenue trends for each product over time to assess growth patterns and predict future sales potential.

Compare total revenue with transaction count by product to find if certain products have higher revenue per transaction, which could inform pricing strategies.

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

For calculating the monthly sales total for the current year, here's how you can explain the query and its relevance to the dataset and project:

Explanation:

1. Purpose:

This query calculates the total sales for each month in the current year. It helps break down the sales performance on a monthly basis, allowing us to track how revenue changes throughout the year, identify seasonal trends, and plan for inventory and marketing strategies based on these patterns.

2. Breakdown:

MONTH(OrderDate): Extracts the month from the OrderDate field, grouping the data by the month of each transaction.

SUM(Quantity*UnitPrice): Sums up the TotalSales for each month, providing the total sales revenue for that month.

WHERE YEAR(OrderDate) = YEAR(CURDATE()): Filters the data to include only the sales transactions from the current year, ensuring the results are relevant for the ongoing year.

GROUP BY MONTH(OrderDate): Groups the results by the month, so we get the sales total for each individual month.

ORDER BY Month: Orders the months in ascending order (from January to December), so the sales data is shown in a chronological sequence.

3. Insight Derived:

This query helps us understand monthly sales trends within the current year. We can identify peak sales months, typically during seasonal spikes (e.g., holidays, special promotions), and recognize months with slower sales, which can inform decisions on inventory, marketing campaigns, and sales strategies.

4. Relevance to the Dataset and Project:

This query fits well within the broader sales analysis of the project. By providing monthly sales totals, it complements other metrics such as total revenue per product or highest-selling product by showing how product performance varies over time.

Understanding the sales distribution throughout the year is valuable for making informed business decisions, such as adjusting sales targets, optimizing stock levels, or planning future promotions.

5. Potential Next Steps:

Compare monthly sales with product category performance to determine which products contribute most to sales in specific months.

Use this data to forecast sales for upcoming months, leveraging historical trends to plan better for future demand.

Compare current year sales with previous years to assess growth and identify trends or anomalies in monthly performance.

 6.find the top 5 customers by total purchase amount.
```

SELECT TOP 5 CustomerID, SUM(Quantity*Unitprice) AS Total_Purchase_Amount FROM [dbo].[SalesData]
GROUP BY CustomerID
ORDER BY Total_Purchase_Amount DESC
```

![Screenshot (189)](https://github.com/user-attachments/assets/90212d99-4503-49d5-9cf6-588a61e70a22)

1. Aggregation of Total Purchases:

The query is aggregating the total purchase amount for each customer by multiplying Quantity by UnitPrice and summing the results. If multiple customers are purchasing the same or similar items in similar quantities, it is possible for their total purchase amount to be the same. This could happen due to:

Multiple Customers Purchasing the Same Product(s): Several customers might have bought the same product(s) in identical quantities, leading to the same total purchase amount.

Small Variations in Purchase Patterns: Even if customers are purchasing different products, if their combined purchases add up to the same total (e.g., Customer A buying 3 items for $7 each and Customer B buying 2 items for $10 each), their total purchase amount will be the same.

2. Similar Purchase Patterns:

The results might indicate that these 5 customers have similar purchase behaviors, i.e., they have made purchases of similar size or value.

This could be a common behavior if certain products are more popular and are purchased in bulk by multiple customers, or if customers have purchased during a sale or a promotional period where similar quantities were bought.

3. Statistical Significance:

From a statistical perspective, it is common to observe identical totals for multiple customers in large datasets, especially if the product range and quantities are consistent across the customer base. In your case, these customers might have purchased the same combination of products, which resulted in the same total sales value.

4. Business Insights:

If the goal is to understand the buying patterns of top customers, you can delve deeper into the specific items they purchased. For instance, you can examine the order details for these customers to see if they are buying the same or similar products. This can give insight into product popularity, sales events, or trends.

It might be valuable to analyze the product categories in conjunction with customer purchase amounts to see if certain products or product groups are driving these similar purchase amounts.

5. Interpretation of the South Region:

If the query shows that all five customers are from the same region (e.g., South), this could indicate that a specific region has higher sales volume or that a certain promotion, product, or sale event was particularly popular in the South region during the period analyzed.

It could also suggest that the South region has a concentrated group of customers purchasing at similar levels, which could be important for sales strategy, marketing, or inventory management in that region.

Additional Actions for Deeper Insights:

Investigate Specific Orders: If you're interested in understanding why these customers have the same total purchase amounts, you can look into the details of their individual orders. This can help you identify whether the same products were purchased or if there is a trend in the types of purchases.

Consider Other Metrics: To get more granular insights, you can consider other metrics like:

Average Quantity Purchased per Customer: Instead of focusing on the total purchase amount, you might analyze the average quantity purchased to see if it explains the same total amounts.

Product Categories: Investigating if certain products or categories contributed to these identical purchase amounts.

7. calculate the percentage of total sales contributed by each region.
```
SELECT region, 
       SUM(quantity * unitprice) / (SELECT SUM(quantity * unitprice) FROM [dbo].[SalesData]) * 100 AS percentage_sales
FROM [dbo].[SalesData]
GROUP BY region
```
![Screenshot (191)](https://github.com/user-attachments/assets/17e5b5f2-1380-400a-938e-6fba70411218)

Explanation:

SUM(Quantity * UnitPrice): This calculates the total sales for each region.

SELECT SUM(Quantity * UnitPrice) FROM SalesData: This calculates the total sales for all regions.

(SUM(Quantity * UnitPrice) / (SELECT SUM(Quantity * UnitPrice) FROM SalesData)) * 100: This divides the total sales for each region by the total sales of all regions and multiplies by 100 to get the percentage.

GROUP BY Region: This groups the data by region, so you can calculate the sales for each region individually.

ORDER BY SalesPercentage DESC: This orders the regions by the percentage of total sales in descending order, so the region with the highest sales contribution is shown at the top.

Total Sales: The total amount of sales for each region.

Sales Percentage: The percentage of the overall sales that each region contributes.

Insights and Business Application:

Sales Distribution by Region: This calculation helps identify which regions are generating the most sales. For instance, if the South region is contributing 25% of the total sales, this indicates it is the highest-performing region in terms of revenue.

Strategic Focus: This analysis can guide business decisions, such as targeting underperforming regions or increasing marketing efforts in top-performing regions.

Product Distribution: You may want to follow up with more detailed analysis by looking at which products or categories are driving sales in the top regions.

Summary Explanation for Your Report:

"The total percentage sales contributed by each region provides a clear picture of regional sales performance. By calculating the sales for each region as a proportion of the overall sales, we can identify the regions that are driving the most revenue. This insight is valuable for making strategic decisions related to marketing, inventory, and sales efforts, allowing businesses to focus on high-performing regions and address potential opportunities in underperforming regions.

8. identify products with no sales in the last quarter.
```
SELECT DISTINCT Product FROM [dbo].[SalesData]
WHERE PRODUCT NOT IN (SELECT DISTINCT Product FROM [dbo].[SalesData]
WHERE OrderDate >= DATEADD(QUARTER, -1, GETDATE()))
```
![Screenshot (190)](https://github.com/user-attachments/assets/92df6a5a-ac07-4e2c-abe4-d57f541e9a61)

"By identifying products with no sales in the last quarter, we can pinpoint underperforming products that may require marketing efforts, discounts, or even delisting. This analysis helps optimize the product portfolio and ensure that resources are focused on products that contribute to overall sales, while also addressing any potential issues with slower-moving products."
### Interactive Power BI Dashboard

![Screenshot (268)](https://github.com/user-attachments/assets/e094f8d6-273b-4788-a762-04da4caca80c)

### Key Strategies and Recommendations
---

# Products Based
**Revenue Concentration:** With **80% of the revenue generated by the top four products** (shoes, shirts, hats, gloves), the data suggests that the company's success heavily relies on a few key items. This revenue concentration could present risks if demand shifts away from these core items, so diversifying product appeal might be beneficial.

**Growth Focus** Shoes and shirts, as the leading products, represent a potential focus area for driving further growth, as well as for exploring customer satisfaction, marketing, or product development to maintain and capitalize on this interest.

**Potential for Product Review:** The lower performance of socks and jackets raises questions about their market fit. This could be an opportunity to understand why these products underperform and, based on customer feedback, consider whether these items need promotion adjustments, design changes, or reallocation of resources.

#Region Based

Recommendation: Consider using the South as a case study to understand what products, promotions, or services drive high revenue. The business could then strategically expand similar approaches into underperforming regions, adapting them as needed for local customer preferences.

- Focus resources on the South to maximize sales further, potentially with high-margin products or new product lines.

- Scale successful strategies from the South into other regions, especially East and North, where there’s potential for growth.
  
- Use a data-driven approach to optimize marketing, inventory, and product offerings in each region, aligning efforts to maximize revenue based on regional demand patterns.

**Region-Specific Product Strategies**

Each region has a unique product profile:

- South: Given shoes’ popularity, consider adding complementary products like socks or sports accessories that would attract shoe buyers.

- East: Shirts’ success here indicates that clothing, rather than accessories, drives sales. Campaigns highlighting clothing, particularly shirts and jackets, could be effective.

- North and West: Both regions show a variety of product preferences. The North prefers shirts and jackets, while the West shows interest in hats and gloves. Tailored promotions for each region can capitalize on these preferences.

** Opportunities for Low-Performing Products**

Shoes struggle in the East and West, while accessories like gloves and hats are more successful there. You might test new marketing angles for shoes in these regions to gauge response or explore bundling options to boost sales.

Socks have a smaller share across all regions. If inventory costs are low, socks could be bundled with high-performing products to increase volume. Alternatively, reallocating marketing efforts for socks to other regions or product lines might free up resources for more promising items.

**Potential Product Gaps and Cross-Region Learning**

The East and North regions favor shirts and jackets, hinting at a broader interest in casual or outerwear. If this trend is underdeveloped in the South or West, introducing these items there could capture a wider market.

Leveraging cross-region insights may reveal untapped potential. For instance, if hats perform well in the West but not elsewhere, trial campaigns in other regions might uncover latent demand.

**Actionable Recommendations**

- Regional Promotions: Craft product-specific campaigns tailored to regional preferences (e.g., emphasize shoes in the South, shirts in the East and North, hats in the West).

- Bundling Strategies: Bundle high and low-performing products (e.g., socks with shoes in the South, gloves with hats in the West) to increase exposure for low-performing items.

- Seasonal Adjustments: Consider if regional product popularity aligns with seasonality (e.g., gloves and jackets in colder months) and adjust inventory and marketing accordingly.

- Expand Popular Product Lines: Introduce variations of popular products in regions where they are successful. For instance, offer more styles or types of shirts in the North and East, or expand the shoes line in the South.

By using these insights to guide marketing and product strategies,  effectiveness of regional approach can be enhanced, improve inventory allocation, and potentially increase sales across each region.

**Yearly Trends**
- Early-Year Sales Focus: With January showing strong growth, investing in January-specific promotions or campaigns might yield strong returns. Expanding successful January strategies into February and March could also sustain early momentum.

- Examine July’s Drop: Since July was significantly weaker in 2024, it’s worth investigating what changed in that month (e.g., market competition, consumer spending trends, seasonal factors). Adapting the sales approach or running targeted promotions in July 2025 might help mitigate any similar downturns.

- Build on August Success: August saw considerable improvement in 2024. This could indicate an opportunity to drive even more sales with back-to-school promotions or end-of-summer sales. Highlighting high-demand products from August in future promotions may capitalize on this trend.

- Plan for Strong Q4: Based on Q4 2023 performance, the business may anticipate a revenue spike in October and November, especially as the year-end approaches. Allocating resources or preparing inventory for these months could maximize returns.

The variations in monthly revenue between 2023 and 2024 suggest both seasonal demand and potentially external factors (like promotions, competition, or economic conditions) impacted sales performance. Understanding these patterns allows the business to refine its strategy, focusing on high-performing months, exploring the reasons behind downturns, and potentially adjusting marketing and inventory plans to enhance future performance.

### Conclusion
---

In the analysis, a divergence between total revenue and average sales per product:

- Shoes generate the highest revenue in the dataset, which aligns with their strong sales volume, making them the highest-performing product in terms of overall sales. This indicates that shoes are likely a popular, high-demand product, contributing significantly to the company's top line. However, in terms of average sales per product, shoes rank second, behind shirts. This could suggest that while shoes are sold in large quantities, they are priced lower than shirts or other products, reducing the average sales per product.

- Shirts, although generating lower overall revenue than shoes, come in first in average sales per product. This suggests that shirts, while possibly sold in fewer quantities, are priced higher, driving a greater sales value per unit. This makes shirts a high-value item, and their strong performance in average sales indicates they may appeal to a more premium market or benefit from higher pricing or margins.

This insight reveals the importance of both sales volume and pricing strategies when analyzing product performance. While high-revenue products (like shoes) show volume-driven success, products with higher average sales per unit (like shirts) might be key to profitability and premium market targeting.

These observations highlight the need to balance both revenue generation and pricing strategies to understand the true drivers of business success.

By aligning product, region, and seasonal strategies, the business can maximize its strengths and target areas with high growth potential. Continued analysis of these areas will help refine strategies over time, enabling the business to respond to market trends and capitalize on emerging opportunities. This data-driven approach ensures a well-rounded strategy that will support sustainable growth and a competitive edge in the market.









