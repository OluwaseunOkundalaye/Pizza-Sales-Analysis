# Pizza Sales Analysis
An Excel project analyzing a year's worth of sales from a fictitious pizza sales place. The dataset encompasses details such as pizza type, size, quantity, price, and ingredients. The goal is to derive actionable insights to inform strategic decisions and optimize overall operational effectiveness.

## Table of Contents

[Project Overview](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/edit/main/README.md#project-overview)

[Project Scope](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/edit/main/README.md#project-scope)

[Project Objectives](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/edit/main/README.md#project-objectives)

[Expected Outcome](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/edit/main/README.md#expected-outcome)

[Document Purpose](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/edit/main/README.md#document-purpose)

[Use Case](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/edit/main/README.md#use-case)

[Data Source](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/edit/main/README.md#data-source)

[Data Cleaning and Processing](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/edit/main/README.md#data-cleaning-and-processing)

[Data Analysis](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/edit/main/README.md#data-analysis-and-insight)

Data Visualization

Recommendation

Conclusion

## Project Overview

This project involves an in-depth analysis of a year's worth of sales data from a fictitious pizza place. The analysis is performed using Excel, providing valuable insights to drive strategic decisions and optimize operational effectiveness.

## Project Scope

The project covers a comprehensive analysis of pizza sales, including order details, orders, pizza types, and pizzas. The analysis spans a full year, providing a detailed view of operational performance during this period.

## Project Objectives

The primary objectives of this analysis are:

-	 **Sales Analysis:** Understand sales patterns over the year, identifying peak times and high-demand periods.

-	**Product Performance:** Evaluate which types and sizes of pizzas are most popular and generate the most revenue.

-	**Customer Preferences:** Analyze ingredient popularity and preferences to refine the menu offerings.

-	**Operational Insights:** Uncover inefficiencies and areas for improvement in operations and supply chain management.

## Expected Outcome

The analysis aims to provide actionable insights, including:

-	Daily customer count.

-	Identification of peak hours.

-	Average number of pizzas per order.

-	Identification of bestsellers.

-	Revenue analysis.

-	Detection of seasonality in sales.

-	Recommendations on menu optimization and promotional strategies.

## Document Purpose

This documentation serves as a guide for project stakeholders, providing insights into the project's objectives, data sources, data analysis, visualizations, and other relevant information.

## Use Case

Stakeholders Benefiting from the Analysis

**1.	Business Owners and Management**

-	**Decision-Making Support:** Provides insights into sales trends, product performance, and customer preferences for informed strategic decisions.
  
-	**Revenue Optimization:** Identifies high-demand products and peak sales periods, enabling targeted promotions and optimized pricing strategies.

**2.	Marketing Team**

-	**Targeted Campaigns:** Enables the development of targeted marketing campaigns based on customer preferences and popular products.
  
-	**Promotional Strategies:** Assists in designing effective promotional strategies to maximize impact during peak sales periods.

**3.	Operational Team**

-	**Staffing Efficiency:** Helps make better staffing decisions by identifying peak sales times.
  
-	**Process Improvement:** Provides a basis for process improvements to enhance productivity and service quality.
  
This comprehensive analysis equips each stakeholder with the insights needed to drive business growth, improve operational efficiency, and enhance customer satisfaction.

## Data Source

The dataset for this project is sourced from [Maven Analytics](https://app.mavenanalytics.io/datasets?dataStructure=Multiple+tables&accessType=open) website, designed specifically for practice purposes. It is presented in an Excel file with four tables (Order Details, Orders, Pizza Types, and Pizzas) comprising 48,620, 21,350, 32, and 96 rows respectively, and 4, 3, 4, and 4 columns respectively. The dataset includes key attributes essential for a comprehensive analysis, such as:

-	Order_id: Unique identifier for each order.
  
-	Date: Date the order was placed.
  
-	Time: Time the order was placed.
  
-	Order_details_id: Unique identifier for each pizza within each order.
  
-	Pizza_id: Foreign key linking to pizza details (size and price).
  
-	Quantity: Number of each type and size of pizza ordered.
  
-	Pizza_type_id: Foreign key linking to pizza type.
  
-	Size: Size of the pizza.
  
-	Price: Price of the pizza in USD.
  
-	Name: Name of the pizza as shown in the menu.
  
-	Category: Category of the pizza in the menu.
  
-	Ingredients: Ingredients used in the pizza as shown in the menu.
  
Each of these variables contributes crucial insights, collectively painting a vivid portrayal of Pizza Sales Place.


## Data Cleaning and Processing

Having clean data for analysis is essential because it ensures that the insights are accurate, reliable, and free from errors. Clean data makes the analysis process smoother, helping researchers, analysts, and decision-makers to draw meaningful conclusions and make informed decisions based on trustworthy information.
After thoroughly checking the data for quality and suitability, including looking for errors, inconsistencies, missing values, and duplicates, I found that the dataset is well-organized and consistent except the order_id column which requires the PROPER function to ensure that each word begin with an upper case. The data follows a standard format and uses consistent names. All the necessary fields are present and filled out correctly. The data values are accurate, and each column has the correct data type. Importantly, there are no duplicate records.

Based on this detailed review, the dataset is well-prepared and ready for analysis, ensuring that the insights I gain will be accurate, reliable, and trustworthy.

**Additional Data Processing Steps:**

**1.	Extraction of Columns:**

To create a unified dataset for comprehensive analysis, various columns were extracted from other tables and integrated into the Order Details table using the VLOOKUP function in Excel. These columns included Date, Time, Size, Price, Name, Pizza Type ID, Category, and Ingredients. This step ensured that all necessary information was consolidated into a single table, facilitating easier and more efficient analysis.

**2.	Addition of New Columns:**

Several new columns were added to enhance the dataset and enable more detailed analysis. These new columns included:

-	**Month:** This column represents the month in which each order was placed, allowing for the analysis of monthly sales trends.
  
-	**Day:** This column indicates the day of the week for each order, helping to identify the busiest days.
  
-	**Quarter:** This column denotes the fiscal quarter in which each order occurred, providing insights into quarterly performance.
  
-	**Revenue:** Calculated by multiplying the price of each pizza by the quantity ordered, this column captures the revenue generated by each order.
  
-	**Full Size:** This column expands on the Size column, providing a more detailed description of the pizza size for better analysis.
  
These additional columns are crucial for examining sales trends over time, identifying seasonal patterns, and determining peak sales periods.


## Data Analysis and Insight

The primary aim of this analysis is to derive valuable insights from Pizza Sales Place data by conducting a comprehensive examination of key factors. This multifaceted exploration involves several pivotal objectives. Firstly, it seeks to know how many customers Pizza Sales Place have each day and if there are any peak hours of orders. Secondly, the analysis aims to identify how many pizzas are typically in an order and if there are any best seller. Thirdly, a detailed investigation into how much money was made this year and if there is any seasonality in sales. In addition, this analysis seeks to know if there should be any pizza to be taken off the menu and if there are any promotion it can leverage on. Lastly, to know if any category is to be taken out of the menu and how they have contributed generally to the sales. 

Key benefits include, Operational Efficiency: Improves staff scheduling and inventory management, Customer Insights: Identifies peak and slow days, Financial Planning: Aids in revenue projections and cost management, Strategic Decision-Making: Informs marketing campaigns and menu optimization, Customer Experience: Enhances service quality and engagement strategies.

As a result, this analysis provides insights addressing the following questions.

**1.	How many customers do we have each day?**

The primary objective of this analysis is to determine the daily customer count at Pizza Sales Place using the order_id as a proxy for individual customer transactions. This information helps in understanding the daily customer flow, identifying peak and slow periods, and optimizing business operations. 

To achieve this, a pivot table was created. The day column was placed in the row section, and order_id was placed in the value section to count the number of orders. The results were visualized using a bar chart.

![](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/blob/main/Number%20of%20Customers%20Per%20Day.png)

From the above analysis

-	Friday has the highest customer count (8106). Popular for social gatherings and end-of-week treats.
	
-	Saturday has second highest (7355). Continued high activity due to leisure and social activities.
	
-	Thursday with 7323 customers, indicating a steady increase as the weekend approaches.
	
-	Tuesday and Wednesday shows approximate consistent mid-week count (6753 and 6794), reflecting stable dining habits.
	
-	Monday shows slight dip (6369), likely due to the start of the workweek.
	
-	Sunday has the lowest count (5917), possibly due to home-cooked meals or different activities.

**2.	Is there any peak hour for customers order?**

The primary aim of this question is to identify the specific times of the day when Pizza Sales Place experiences the highest volume of customer orders. Understanding peak hours is crucial.

To achieve this, a pivot table was created. The time column was placed in the row section which was set to hours, and order_id was placed in the value section to count the number of orders. The results were visualized using a bar chart.

![](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/blob/main/Total%20Customer%20Per%20Hour.png)

From the analysis above

- 12 PM: The highest customer count occurs at 12 PM with 6,543 customers, indicating lunchtime as the busiest period.
 
- 1 PM: Following closely, 1 PM has 6,203 customers, reinforcing the lunchtime rush.
 
- 6 PM: The evening rush starts at 6 PM with 5,359 customers.
 
- 5 PM: Just before the peak evening rush, 5 PM sees 5,143 customers.
 
The busiest times for Pizza Sales Place are during the lunch (12 PM - 1 PM) and evening (5 PM - 7 PM) periods. The business experiences moderate customer flow during the early afternoon and later evening hours. Very little to no activity is observed late at night and early in the morning. 

**3. How many pizzas are typically in an order?**

The aim of this question is to understand the average quantity of pizzas customers order per transaction. This metric can provide several valuable insights, including order size, stock levels, efficiency, sales projections, and order customization.

To determine the average number of pizzas per order, two pivot tables were created, the quantity column was added to the "Values" section and set to "Sum" to calculate the total number of pizzas ordered. The quantity column was added to a second pivot table and set to "Count" to determine the total number of orders. Using these pivot tables, the sum of quantities was found to be 49,574, and the count of quantities was 48,620. The average number of pizzas per order is calculated as follows:

```Average Quantity = (Sum of Quantities)/(Count of Quantities)=  49,574/48,620 = 1```

This calculation shows that the average number of pizzas per order is approximately 1.

**4. Do we have any bestsellers? Are there any pizzas we should take of the menu, or any promotions we could leverage?**

This question aims to understand the popularity and financial impact of different pizza. By identifying top-selling products, least-selling products, and those driving the most revenue, the business can make informed decisions about inventory management, marketing strategies, and potentially introduce promotions or adjustments to product offerings.

The determination of the top and least selling products was based on analyzing sales data to identify items that customers frequently purchase in higher quantities or sold less frequently. In Excel Power Pivot, a measure was created to calculate the total quantity sold for each product. Subsequently, a bar chart was employed as a visualization tool to display the results. To enhance clarity and focus on significant insights, the filter pane was employed to display only the top 5 best-selling products and the least 5 selling products, determined by quantity sold.

![](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/blob/main/Top%205%20Selling%20Pizzas%20By%20Order.png)

- With the highest quantity sold (1811 units), Big_meat_S leading in quantity sold, this product holds a prominent position, suggesting it's a customer favorite and potentially a key revenue driver.
  
- Thai_Ckn_L, Five_Cheese_L, Four_Cheese_L, Classic_Dlx_M, pizza have relatively high quantities sold, suggesting consistent demand across the board. These pizzas, while not the top-sellers, maintain substantial quantities sold, indicating consistent popularity and contributing significantly to overall sales.

![](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/blob/main/Least%205%20Selling%20Pizzas%20By%20Order.png)

- With the lowest quantity sold (28 units), The_Greek_XXL stands out as the least performing product in terms of sales.
  
- Mexicana_S, Calabrese_S, Ckn_Alfredo_S, Green_Garden_L, and The_Greek_Xxl pizzas also exhibit lower quantities sold, indicating a lower level of demand compared to other items.
  
**Best and Least Selling Product by Revenue.**

This determination is based on identifying pizzas that significantly contribute to the overall revenue of the business. The analysis encompasses not only transaction frequency but also considers the interplay of product price and the total sales amount for each item, providing a comprehensive understanding of the key revenue drivers

To identify the best-selling product by revenue in Excel Power Pivot, a dedicated measure was formulated to calculate the total revenue generated by each product. This measure was then utilized in conjunction with a bar chart, serving as a visual representation of the results. In order to streamline the presentation and emphasize key insights, the filter pane was employed to exclusively showcase the top 5 best-selling and least selling pizzas, determined by the quantity sold. This approach ensures a clear and focused view of product performance based on revenue, facilitating strategic decision-making and actionable insights.

![](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/blob/main/Top%205%20Selling%20Pizzas%20By%20Revenue.png)

- Thai_Ckn_L stand out as the top revenue generator leading in total revenue at $29,258.
- Five_Cheese_L, Four_Cheese_L, Spicy_Ital_L, Big_Meat_S, while not the top revenue contributors, these products still exhibit substantial revenue figures, indicating consistent popularity among customers.

![](https://github.com/OluwaseunOkundalaye/Pizza-Sales-Analysis/blob/main/Least%205%20Selling%20Pizzas%20By%20Revenue.png)

- The_Greek_XXL stand out as the least revenue generator with a total revenue at $29,258.
- Calabrese_S, Ckn_Alfredo_S, Grenn_Garden_L while not the least revenue contributors, these products still exhibit low revenue figures, indicating consistent unpopularity among customers.

**5. How much money did we make this year? Can we identify any seasonality in the sales?**

The aim of this question is to assess the total annual revenue and identify any sales patterns that vary over time. This helps understand the financial performance of the pizza place and reveals seasonal trends, providing insights into how sales fluctuate throughout the year.

To achieve this, the monthly sales trend and quarterly sales were determined using pivot tables and plotted on a line chart. While for the total revenue, the revenue column was pivoted and set to sum of revenue. This visualization provides a clear picture of sales dynamics over the year, highlighting any recurring patterns or anomalies that require attention.

```Total Revenue: $817,860```

**Seasonality in Sales**



