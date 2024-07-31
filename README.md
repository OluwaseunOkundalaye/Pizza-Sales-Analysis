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
