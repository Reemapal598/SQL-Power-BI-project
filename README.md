# SQL+Power-BI-project 

## Project Overview: 
This data project provides insights into the sales performance of the coffee shop by analyzing the performance on month - on- month basis, weekdays, weekends, location and various aspects.

## Data Source: 
The data set used for this project is "Coffee Shop Sales.xlsx" file which contain all the information about the coffee shop.

## Business Requirement: 
- Total Sales Analysis: Calculate the total sales for each respective month, Determine the month on month increase or decrease in sales,Calculate the difference in sales between the selected month and the previous month.
- Total Orders Analysis: Calculate the total number of orders for each respective month, Determine the month on month increase or decrease in number of orders,Calculate the difference in number of orders between the selected month and the previous month.
- Total Quantity Sold Analysis: Calculate the total quantity sold for each respective month, Determine the month on month increase or decrease in the total quantity sold,Calculate the difference in the total quantity sold between the selected month and the previous month.
- Sales Volume: Represent sales volume on month on month basis with higher sales marked in darker shade, tooltip to show detail metric of Sales, Orders & Quantity when hoverover the specific day.
- Sales Analysis by Weekdays and Weekends: Show sales data into weekdays and weekends to analyze performance variations, Provide insights whether sales performance differ between weekdays and weekends.
- Sales Analysis by Store Location: Sales by different location, Include month-over-month(MoM) difference metrics based on selected month in slicer, Highlight MoM sales increase or decrease of each location to identify sales trends.
- Daily Sales Analysis with Average Line: Show daily sales for the selected month, Show average daily sales by representing average line, Highlight bars exceeding or decreasing below the average sales to identify exceptional sales days.
- Sales Analysis by Product Category: Sales perofrmance by different product category, Show which product categories contribute to the most overall sales.
- Top 10 Products by Sales: Identify and display the top 10 products based on sales.
- Sales Analysis by Days and Hours: Sales pattern by days and hours, tooltip to show detail metric of Sales, Orders & Quantity when hoverover the specific day-hour.

 ## Tools:
- SQL Workbench - Data Analysis
- PowerBI - Creating report

## Findings: (The finding differ on month on month basis, below is for the month of Feb’23 & March’23) 

1.	Analyzed the total Sales, Orders & Quantity sold on month-on-month basis and calculated the difference in the performance with the previous month. 
Feb 2023: 
•	Total Sales: 76K which is decreased by -6.8% as compared to Jan’23
•	Total Orders: 16359 which is decreased by -5.5% as compared to Jan’23
•	Total Quantity Sold: 23550 which is decreased by -5.3% as compared to Jan’23
   From March’23 onwards there has been substantial increase in the performance of sales.
2.	Calendar heat map is created to analyze the sales performance of each day on specify month with the help on slicer. Darker shade indicates good sales while the lighter shade indicates poor sales performance. Data for 8th ,9th 10th, 13th ,24th & 27th March’23 indicates good performance with total sales above $3000K
3.	There is a significant difference in the sales performance over the weekdays and weekends. The total sales $99K out of which weekdays contribute to the maximum sales around $73K and lowest on weekends with $25K barely achieving the average sales of $3,188.
4.	The stores are location at 3 different locations, Hell’s Kitchen stop the chart with total sales of $33,111K for the month on March’23 with a increase in the performance by +28.7% as compared to Feb’23.
5.	Daily sales trend is created by line chart and an average line is created indicating the daily average sales. Bars highlighted in darker shared indicate good sales performance by crossing the average sales line. For the month of March’23 the highest sales done was on 27th March with total sales on $3,674K
6.	Analyzed sales performance across different categories out of which Coffee contribute to $38,304K sales followed by Tea ($27.91K) & Bakery ($11.90K)
7.	There are top 10 products as per the sales volume. Barista Espresso contribute the highest ($13,078K) and the least is Dip Coffee ($4,561K)
8.	Sales pattern as per hours & days (weekdays & weekends) maximum sales are contributed during the morning hours from 7.00AM to 10.00AM with a maximum sale of $12,058K. Saturday & Sunday been a weekend the sales performance is pretty fine with $12,783K & $12,684K. Wednesday, Thursday & Friday been a weekday we have good sales of around $16,253K.




  
        










 
