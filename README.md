
# Electrohub Sales Data Analysis - Power BI Dashboard
## Overview

This project provides an interactive Power BI dashboard for analyzing sales data of Electrohub, a fictional electronics retailer. The dashboard aims to deliver actionable insights into sales performance, product performance, customer behavior, and promotion effectiveness. By visualizing key metrics and enabling dynamic exploration, this dashboard empowers Electrohub to make data-driven decisions to optimize their business strategies and drive growth.

## Problem Statement

Electrohub needs to gain a deeper understanding of its sales data to optimize business strategies and achieve sustainable growth.  This dashboard addresses key business questions such as:

1) Top/Bottom 5 product by Sales/Profit/Quantity Sold.2) How do sales trends vary over time (daily, monthly, quarterly, annually) 
3) Show relationship between sales & profit.
4) Compare sales/profit/quantity sold between any two periods selected by the user.
5) Average discount offered in each discount category.
6) Total number of orders.
7) Show Sales/Profit/Discount/Net Sales/All remaining fields for each order that could be filtered using visual filters. (Product/Date/Customer ID/Promotion Categories)
8) Show sales by different cities.

By answering these questions, Electrohub can identify areas for improvement, capitalize on successful strategies, and ultimately enhance profitability and market share in the competitive electronics retail market.

## Steps Followed

The development of this Power BI dashboard involved the following key steps:

1.  **Data Acquisition:** Extraction of sales data from Electrohub's data sources.
2.  **Data Transformation & Cleaning (Power Query):**  Utilizing Power Query to clean, transform, and prepare the data for analysis, including handling inconsistencies and ensuring data quality.
3.  **Data Modeling (Power BI Desktop):**  Designing and implementing a star schema data model in Power BI, linking fact tables to dimension tables for efficient data analysis and reporting.
![Image](https://github.com/user-attachments/assets/433665f6-7046-4160-b922-6a2a5bf235b5)
4.  **DAX Measure Creation:** Developing Data Analysis Expressions (DAX) to create calculated measures for key performance indicators (KPIs) such as Total Revenue, Profit, Profit Margin, YOY Growth, etc.

5.  **Dashboard Design & Visualization:**  Designing an intuitive and interactive dashboard layout using Power BI's visualization tools to effectively present insights and enable data exploration.

6.  **Interactive Feature Configuration:**  Implementing interactive elements like slicers and cross-filtering to enhance user experience and enable dynamic data exploration.
7.  **Testing and Refinement:**  Thorough testing of the dashboard for accuracy, performance, and usability, followed by iterative refinements based on testing feedback.


## Dashboard Components

The Power BI dashboard is structured into several interactive pages, each focusing on a specific aspect of sales analysis:

### 1. Overview
![Image](https://github.com/user-attachments/assets/13424651-feca-4ada-9b0d-128beaa2fc67)
- **Description:**  Provides a high-level summary of Electrohub's sales performance. Key metrics include Total Revenue, Units Sold, and Year-over-Year (YOY) growth. This page gives an immediate snapshot of overall business health.

### 2. TOP/BOTTOM ANALYSIS
![Image](https://github.com/user-attachments/assets/74fb6b76-9176-44ee-aaa9-3e2568c27735)
- **Description:**  Identifies the top 10 and bottom 10 performing products based on both revenue and profit margin. This analysis helps pinpoint successful products and areas that require attention or strategic adjustments.

### 3. Comparison Sales/ Profit/ Quantity

![Image](https://github.com/user-attachments/assets/b8609170-c9f3-468a-8928-7bcc9ed6a4c9)
- **Description:**  Offers an interactive comparison of Profit, Sales, and Order Quantity across different Regions and Product Categories. This visualization allows for understanding the drivers of sales and profitability in various segments of the business.

### 4. Edit Interactions
![Image](https://github.com/user-attachments/assets/71160cbd-0576-4613-8209-d2bcba11c543)

- **Description:** Demonstrates the configured cross-filtering interactions between different charts and visuals within the dashboard. Selecting data points in one visual dynamically updates related visuals, enabling users to explore data relationships and drill down for deeper insights.

### 5. Table-visual
![Image](https://github.com/user-attachments/assets/6cd02777-7156-4411-b3c4-f489b5c4feee)
- **Description:** Presents a detailed table view of the sales data, enhanced with slicers for **Date**, **Customer Name**, **Product Name**, and **Promotion Name**. Users can leverage these slicers to dynamically filter the data and perform granular analysis on specific segments or transactions.


## Technologies/Tools Used

*   **Power BI Desktop:**  For data modeling, DAX calculations, visualization creation, and dashboard design.
*   **Power Query Editor:**  For data extraction, transformation, and cleaning.
*   **GitHub:** For version control and project hosting (if applicable).

## How to Use

1.  **Download Data and the `.pbix` file:**
    *   **Download the Excel Data:** You can download the Excel data file (`Store Data.xlsx`) used for this analysis from here: https://github.com/Medha-77/Sales-Performance-Analysis-for-Electrohub/blob/main/Store%2BData.xlsx.
    *   **Download the Power BI Report:** Download the `Electrohub.pbix` file from here: https://github.com/Medha-77/Sales-Performance-Analysis-for-Electrohub/blob/main/Electrohub.pbix.

2.  **Open in Power BI Desktop:** Open the downloaded `.pbix` file using Microsoft Power BI Desktop application.
3.  **Explore the Dashboard:** Navigate through the different dashboard pages (Overview, TOP/BOTTOM ANALYSIS, etc.) using the page tabs at the bottom.
4.  **Interact with Visuals:** Click on charts, tables, and slicers to filter and explore the data dynamically. Use slicers to narrow down the data by Date, Customer, Product, or Promotion.
