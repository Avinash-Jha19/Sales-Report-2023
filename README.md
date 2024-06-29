# Sales-Report-2023

Welcome to the Sales Dashboard 2023 project repository. This project demonstrates comprehensive data analysis and visualization using Power BI. It focuses on presenting actionable insights for improving sales performance through detailed monthly sales analysis, sales pattern analysis, and event impact analysis.

## Project Overview

This project aims to build a sales dashboard for the year 2023 using all available data files. The dashboard is designed to facilitate data-driven decision-making by providing clear and insightful visualizations. The analysis covers the following areas:
1. Monthly sales analysis to identify top-performing categories, sales channels, warehouses, and states.
2. Analysis of sales patterns on weekdays versus weekends.
3. Examination of sales trends during specific events.

[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiZGJkNDQ5M2QtMjQzMy00MDdkLTlkYjAtMjhjYThjNzg1NTI2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=74d34435fe098636ae5b)

## Tech Stacks

- Power BI Desktop
- Excel
- DAX language
- Power Query

## Project Charter

- **Monthly Sales Analysis:** Identifying which categories, sales channels, warehouses, and states are performing well.
- **Sales Pattern Analysis:** Visualizing patterns in weekday and weekend sales.
- **Event Impact Analysis:** Analyzing if sales are skewed during specific events.

## Power BI Techniques Learned

- Creating calculated columns
- Creating measures using DAX language
- Data modeling
- Dynamic page navigation with buttons
- Dashboard designing
- Using the divide function to prevent zero division errors
- Toggle Button
- Dynamic Slicers
- Using KPI indicators
- Conditional formatting of values in visuals using icons or background color
- Data Validation techniques
- Report Optimization
- Adding Last Refresh Date
- Adding Last Sales Month

## Power BI Services

- Publishing reports to Power BI services
- Setting up a personal gateway for auto-refresh of data
- Power BI App creation
- Collaboration, workspace, access permissions in Power BI services

## Dataset Understanding

Understanding available data is crucial before performing analysis. Ensure a good understanding of the available data before jumping into the analysis.

### Dimension Tables

1. **Date Calendar:**
   - Columns(10): 
      - Date
      - Week (week number)
      - Month (month name)
      - Day Number (day number of a week)
      - Day (day name)
      - Status (weekday or weekend)
      - Quarter
      - Event - USA (5 distinct events: C7, Normal, President Day 2023, Wayday 2023, Wayday 2.0 2023)
      - Season (Fall, Spring, Summer, Winter)
      - Year (2023).

2. **SKU Details:**
   - Columns(3):
       - SKU (498 distinct SKUs)
       - Category (24 distinct categories)
       - Type (Small Furniture and Large Furniture).

### Fact Table

1. **Sales Data:**
   - Columns(7):
       - PO Date
       - SKU (498 distinct SKUs)
       - Quantity (quantity sold for each SKU on a particular date)
       - Per Unit Price (per unit price of each SKU)
       - Warehouse Region (11 distinct warehouse regions)
       - Sales Channel (8 distinct sales channels)
       - Destination Country (17 distinct destination countries).

## Importing Data into Power BI

Since the data is in Excel workbooks, the datasets are imported directly into Power BI by connecting to the Excel files.

## Data Model

Data modeling plays a vital role and is considered the foundation of the report. All visuals are built upon the data model. Poor data modeling affects the overall performance of the report. In this project, we followed the Star Schema. Refer to this [blog](https://addendanalytics.com/blog/data-modelling-best-practices) to understand good practices.

## Dashboard Design

Based on the requirements received, visual designing and measures will be created as and when required.

## Home View

In Home View, all the view buttons are available. Users will land on a specific page depending on which button they click on. 

- Orders View
- Sales By Status View
- Monthly Analysis View
- Category View
- Warehouse Region View
- Sales Channel View

## Report Overview

![](https://github.com/Avinash-Jha19/Sales-Report-2023/blob/main/Resources/GIF_Complete_Overview.gif)

## Home Page

![](https://github.com/Avinash-Jha19/Sales-Report-2023/blob/main/Resources/GIF_Home_Page_View.gif)

## Orders View

![](https://github.com/Avinash-Jha19/Sales-Report-2023/blob/main/Resources/GIF_Orders_View.gif)

## Sales By Status View

![](https://github.com/Avinash-Jha19/Sales-Report-2023/blob/main/Resources/GIF_Sales_By_Status_View.gif)

## Monthly Analysis View

![](https://github.com/Avinash-Jha19/Sales-Report-2023/blob/main/Resources/GIF_Monthly_Analysis_View.gif)

## Category View

![](https://github.com/Avinash-Jha19/Sales-Report-2023/blob/main/Resources/GIF_Category_View.gif)

## Warehouse Region View

![](https://github.com/Avinash-Jha19/Sales-Report-2023/blob/main/Resources/GIF_Warehouse_Region_View.gif)

## Sales Channel View

![](https://github.com/Avinash-Jha19/Sales-Report-2023/blob/main/Resources/GIF_Sales_Channel_View.gif)

To view the full report 
- [Report](https://github.com/Avinash-Jha19/Sales-Report-2023/blob/main/Sales%20Report%20-%202023.pbix)
- [PDF](https://github.com/Avinash-Jha19/Sales-Report-2023/blob/main/Sales%20Report%202023.pdf)
