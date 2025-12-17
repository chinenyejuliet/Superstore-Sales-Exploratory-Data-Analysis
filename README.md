# Superstore-Sales-Exploratory-Data-Analysis
 This project analyzes sales performance for a US Superstore between 2014 and 2017 using Power BI.

## Project Overview

This project is focused on analyzing sales performance data of a Superstore operating in the United States between 2014 and 2017.

Using Power BI, this project transforms raw sales data into interactive dashboards that provide insights into revenue, profit, customer behavior, regional performance and sales trends over time. The aim is to support data-driven decision-making by identifying patterns, strengths and areas for improvement in the sales operations.

<p align="center">
  <img src="https://github.com/user-attachments/assets/90e37178-a788-468a-bd03-c2f9eed9285d" width="1000" height=400>
</p>

***

## Dataset source and Description

### Sources:
Superstore_data.csv

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
  <img src="https://github.com/user-attachments/assets/dcbf82a3-d2db-41ab-86c5-110084bdb571" width="1000" height=350>
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
The dataset was provided in a clean and structured format. Basic validation checks were conducted to ensure data accuracy, consistency and readiness for analysis.

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

<img width="583" height="410" alt="Data Model" src="https://github.com/user-attachments/assets/4d9623c1-482d-4624-b14f-9954d6bbbbd1" />


***

## Exploratory Data Analysis (EDA)


