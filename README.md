# Superstore-Sales-Exploratory-Data-Analysis
 This project analyzes sales performance for a US Superstore between 2014 and 2017 using Power BI.

## Project Overview

This project is focused on analyzing sales performance data of a Superstore operating in the United States between 2014 and 2017.

Using Power BI, this project transforms raw sales data into interactive dashboards that provide insights into revenue, profit, customer behavior, regional performance and sales trends over time. The aim is to support data-driven decision-making by identifying patterns, strengths and areas for improvement in the sales operations.

<p align="center">
  <img src="https://github.com/user-attachments/assets/39acf027-6a9a-4f28-b0b0-26c65da31b0a" width="1000" height=400>
</p>

***

## Dataset source and Description

### Sources:
Superstore_data.xlsx

### Data Description:

- **Period Covered:** 2014 -2017.
- **Data Points:**
  - Order ID  • Order Date
  - Ship Date • Ship Mode
  - Customer ID  • Customer Name • Segment
  - Sales Rep • Sales Team • Sales Team Manager
  - Location ID • City • State • Postal Code • Region
  - Product ID • Category • Sub-Category • Product Name
  - Sales SQL • Quantity • Discount • Profit  


 <p>
  <img src="https://github.com/user-attachments/assets/39c0f223-536f-4810-97cd-3b39994bf6ee" width="1000" height=350>
</p>

 ***
 

## Objectives of the Project

**The main objectives of this project are to:**
- Analyze overall revenue and profit performance of the Superstore
- Evaluate sales trends across years and months
- Identify top-performing regions, customer segments and product categories
- Assess sales team performance
- Provide actionable insights to improve business strategy and profitability

  ## 🛠 Tools & Technologies
- Power BI
- DAX
- Excel / CSV
- Data Modeling & Visualization


## 🧹 Data Preparation
 - Basic validation checks were conducted to ensure data accuracy, consistency and readiness for analysis
 - Sales, profit and order-related fields were reviewed for completeness
 - Time-based variables such as year, month and day were examined
 - Categorical variables including region, category, sub-category and customer segment were analyzed
 - Removed redundant columns after the data modelling process
 - Standardized data format
 - removed duplicated data

## 🧩 Data Modeling
The primary dataset was initially provided as a single fact order table.

To improve data quality, consistency and analytical performance, the data was modeled into a star schema by creating supporting dimension tables (such as Calender Date, Products, Customer, Location, Ship Mode and Sales Rep).
This approach enabled cleaner relationships, more accurate aggregations and reliable DAX calculations.

The data model follows a star schema design with a central fact table (Fact Orders) connected to multiple dimension tables.They include the following:

### Fact Table:
- Fact Orders: Contains transactional sales data including revenue, profit,
  quantity, and order-level details.

### Dimension Tables:
- **Caleder Date:** Supports time intelligence and trend analysis.
- **Products:** Enables category and sub-category analysis.
- **Customer:** Supports customer segmentation.
- **Region:** Enables geographic performance analysis.
- **Sales Team:** Supports team-level performance evaluation.

<img width="583" height="410" alt="Data Model" src="https://github.com/user-attachments/assets/fdae101c-20d9-4a5a-afb5-7b6f7e69c8b4" />


***

## Exploratory Data Analysis (EDA)
The following EDA techniques were applied to uncover patterns:

- Descriptive statistics to summarize sales and profit performance
- Trend analysis to observe yearly, monthly and daily patterns
- Comparative analysis across regions, categories, and sales teams
- Discount impact analysis to assess profit loss
  
***
  
## Key Performance Indicators (KPIs) 

- Total Profit
- Total Units Sold
- Month-on-Month (MoM) Growth
- Year-on-Year (YoY) Growth
- Profit Margin (%)
- Average Order Value (AOV)
- Total Number of Active Customers
- Active Customers Previous Year
- Net Customer Growth
- Churn Rate
- Total Orders

***

## Dashboard Overview

The dashboard includes the following key components:

- Revenue and Profit Summary Cards
- Revenue and Profit Trend Visuals 
- Revenue and Profit Distribution Charts segmented by region, product category, sub-category and customer segment
- Sales Team Performance Analysis
- Discount Impact and Profit Loss Analysis
- Order and Customer Performance Insights
- Time Series and Daily Trend Insights
  

![superstore powerbi project fin-1_page-0001](https://github.com/user-attachments/assets/6b688210-4eca-4145-97a0-428cd4e048c9)

***

![superstore powerbi project fin-2_page-0001](https://github.com/user-attachments/assets/9f461a43-88c8-4c63-b0fd-4741cf349a0b)


***

## Data Analysis and Insights

- Revenue and Profit Analysis:
  - Over the entire period under review, the Superstore achieved $2.29M in cumulative revenue
  - Technology emerged as the category contributing the highest revenue and profit.
  - The Phones sub-category generated the maximum revenue and profit among all sub-categories.

- Regional Performance:
  - The West region contributed the highest share of total revenue.
  - Other regions such as South, Central, and East showed moderate performance, indicating potential growth opportunities.
  
- Customer Segment Analysis:
  - The Consumer segment generated the highest revenue and profit compared to Corporate and Home Office segments.
  - This suggests that individual consumer purchases are a major driver of sales.

- Sales Trend Analysis:
  - Yearly Trend: Revenue experienced a temporary decline between 2014 and 2015, followed by consistent growth through 2017, indicating a strong long-term upward trend.
  - Monthly Trend: Revenue fluctuated month-to-month, with peaks observed in March, September and November, while lower values were recorded in February, April and July.
  - Orders were highest on Mondays and Fridays, with a noticeable drop on Wednesdays, indicating consistent midweek demand reduction.

- Discount Impact Analysis:
 - The analysis revealed that 70% and 80% discount levels resulted in the highest profit losses, indicating that excessive discounting significantly erodes profit margins.

- Sales Team Performance:
    - The Charlie team recorded the highest sales revenue.
    - The Alfa team recorded the lowest sales revenue, indicating the need for performance review or additional support.

***

## Findings and Interpretation

- Technology products are the most profitable and should remain a strategic focus.
- Seasonal trends suggest opportunities for targeted marketing during peak months and weekdays.
- Strong performance in the West region can be leveraged as a benchmark for other regions.
- Consumer customers are the most valuable segment and should be prioritized in sales strategies.

***

## Recommendations

Based on the analysis, the following recommendations are proposed:
- Increase marketing and inventory investment in Technology and Phones products.
- Implement sales improvement strategies for underperforming regions and sales teams.
- Develop promotional campaigns during low-performing periods to stabilize revenue.
- Strengthen customer engagement strategies for the Consumer segment.
- Insights from customer demographics should be used to design personalized marketing strategies that better target dominant customer groups.

## Conclusion

This Power BI project successfully demonstrates how data visualization and business intelligence tools can be used to analyze sales data effectively. The Superstore Sales Analysis provides clear insights into revenue patterns, customer behavior and operational performance. The findings can support management in making informed decisions to enhance profitability, optimize sales strategies and sustain long-term business growth.


