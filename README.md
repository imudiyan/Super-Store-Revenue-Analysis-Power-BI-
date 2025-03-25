# Super Store Revenue Analysis (Power-BI)
This Power BI project focuses on analyzing Super Store revenue across various locations in the USA, leveraging interactive dashboards to provide key business insights. The objective is to enhance data-driven decision-making through advanced visual analytics.
## High-Level tasks performed
- **Collecting & Exploring Data:** Gathered raw data from multiple sources and analyzed its structure.
- **Cleaning & Preparing Data:** Used Power Query to remove duplicates, adjust data types, fill in missing values, and optimize data for analysis.
- **Building the Data Model:** Structured the data by separating key entities like Products, Customers, and Orders for better insights.
- **Choosing the Right Visuals:** Selected Power BI charts and graphs to best represent revenue trends and business performance.
- **Designing the Dashboard:** Created an intuitive, user-friendly layout that allows seamless interaction.
- **Adding Interactive Features:** Implemented slicers, filters, and drill-throughs to enable deeper analysis.
- **Testing for Accuracy:** Verified data consistency and dashboard functionality.
- **Publishing & Sharing:** Deployed the dashboard to Power BI Service and packaged it into an app for easy access.

## Objective
The aim of this project is to analyze Super Store’s revenue and profit across different aspects—such as product categories, regions, and customer segments—using Power BI’s advanced visualization capabilities.

## Data Scope
-	Time Frame: 2017 - 2020
-	Key Metrics: Revenue, Profit, and Sales Performance by Category, Region, and Customer Segment.

## Data Transformation and Modeling
To make the data more usable and insightful, several steps were taken:
-	**Cleaning & Refining Data:** Addressed various data quality issues by removing duplicates, correcting data types, eliminating empty rows, and filling in missing values.
-	**Structuring Data for Efficiency:** Initially, product, customer, and order details were combined in a single dataset. To enhance performance and facilitate better analysis, these were separated into three distinct queries.
-	**Creating Relationships:** Designed a star schema model to improve performance and enable meaningful analysis.

![image](https://github.com/user-attachments/assets/8d87fad6-a086-4983-a2b0-579a0c32ccea)

## Data Model

The structured data model includes:
-	**Fact Table:** Contains all sales transactions, including revenue and profit details.
-	**Dimension Tables:** Includes details on Customers, Products, Regions, and Date.
-	**Key Metrics & Calculations:** Used DAX formulas to measure revenue growth, profit, and year-over-year performance.

![image](https://github.com/user-attachments/assets/4f142f0d-be1f-47b9-b1fc-bdae9e007470)

## Dashboard Layout and design.
 The Power BI dashboard is structured into several key pages:
-	Main Page: Has navigation links to Overview and Revenue by Measures Pages.
-	Overview Page: A detailed look at overall sales and profitability trends.
-	Revenue by Measures Page: Breakdown of revenue based on product categories, regions, and customer segments.
-	Detail Pages (Drill-through Enabled): Additional insights are accessible through drill-through functionality for in-depth analysis.

![image](https://github.com/user-attachments/assets/6e4300c8-fa79-4473-bb89-970d3882daee)

![image](https://github.com/user-attachments/assets/5b02c0d5-f16d-4635-b205-3e7f6e05ca88)

## Key Insights & Takeaways
-	Total Revenue (2017-2020): $2.3 million
-	Total Profit (2017-2020): $0.29 million
-	Yearly Performance:
    -	Lowest revenue recorded in 2018: $0.47 million
    -	Highest revenue recorded in 2020: $0.73 million
-	Best Performing Region: The West region had the highest revenue.
-	Top-Performing State: California led with $137,652 in revenue.
-	Customer Segment Breakdown:
    -	Consumer segment: 50% of total revenue
    -	Corporate segment: 30%
    -	Home Supplies segment: 18%

This Power BI dashboard equips stakeholders with clear, interactive insights into revenue and profitability trends, helping drive informed business decisions.

## Link

https://www.loom.com/share/7c9b30cb443945fabf5c20461f956bf5?sid=c7636a4b-868f-4b4b-9a3c-87004c5faac9
