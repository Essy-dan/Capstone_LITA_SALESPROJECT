
Sales Data Documentation
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

By aligning product, region, and seasonal strategies, the business can maximize its strengths and target areas with high growth potential. Continued analysis of these areas will help refine strategies over time, enabling the business to respond to market trends and capitalize on emerging opportunities. This data-driven approach ensures a well-rounded strategy that will support sustainable growth and a competitive edge in the market.





```SQL
SELECT * FROM TABEL1
WHERE CONDITION = TRUE
```



