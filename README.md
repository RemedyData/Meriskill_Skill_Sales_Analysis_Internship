# Meriskill_Skill_Sales_Analysis_Internship
Meriskill Internship: Sales Analysis; A deep dive into sales data, aimed at extracting valuable  insights to enhance strategic decision-making.(*The picture below is gotten from Meriskill Website*). 

![Meriskill-Sales-Analysis](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/c9bde950-a927-495a-a188-e780a6298fa3)

***Disclaimer:*** This is not a real company as we know this is a dataset compiled by Meriskill for Internship purposes. 


## Introduction

This is a sales performance analysis. It is done by analyzing data from Sales table which comprises of ORDER ID column, PRODUCT column, QUANTITY ORDERED column, PRICE EACH column, ORDER DATE column, PURCHASE ADDRESS column, MONTH column, SALES column, CITY column, and HOUR column. I used Excel to get an overview of the dataset before importing it into Power BI where the actual analysis was carried out. 

## Problem Statement

The goal of this analysis is to:

- Determine noticable sales trends over time
- Know which are the best and worst selling products
- Identify the company's key customers
- Determine shipping costs across providers
- Finally, the goal is to create data-driven plans that can aid in increasing sales, improving customer satisfaction, and driving the company's growth

## Skills and Concepts Demonstrated:

- Power BI concepts like:
   - Creating key performance indicators (KPIs) and other business calculations
   - Developing general DAX calculations that deal with text and numbers,
   - Performed advanced DAX calculations for solving statistical measures and other mathematical formulas,
   - Data Modelling,
   - Measures,
   - Filters,
   - Tooltips,
   - Page buttons,
   - Data visualization
 
   ---
  ## Data Source:
  
The dataset for the work is gotten from Meriskill. It consist of 185,951 records and 11 fields of data. I studied the dataset well to gain proper insight into the dataset. You can find a link to download the dataset [here:](https://drive.google.com/drive/folders/1IlsIC66p5HGBtNkntD872Gkx1j_3Nwdd?usp=drive_link)

   ---

## Data Transformation:

## STEP 1:
I downloaded the dataset, uploaded it using the 'Get Data' option in Power BI, 
and then proceeded to transform the data.

## STEP 2:
The column headers are identified in the first row and kept them as 
headers by following the steps below.

![Meriskill-2](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/afe5b7e6-fc24-43e2-b5a7-e00743b2d864)


## STEP 3:
• After promoting the headers, I navigate to the 'Transform' tab and select 
'Detect Data Type.' This action automatically identifies the data type 
of each column and convert them as needed.

![Meriskill-3](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/a19ffa33-3726-4163-a0cb-392ae452763b)


## STEP 4:
• I split the datetime into date and time stamp

![Meriskill-4](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/ecc22a6a-b560-42ee-9709-ef49a13802b2)

• The aforementioned process starts with selecting the desired column. 
Following the selection, the option to split the column becomes visible.

![Meriskill-4a](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/4df5a285-1a96-4545-9d77-530b9c704acc)

• I chose the 'Split Column' option and select the space as the delimiter. 
• Upon completing the data transformation, I clicked on 'Close & Apply' 
located at the top left of the menu bar.

![Meriskill-4b](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/2215af3c-32f5-4156-9638-ceca5f9c7023)






---

## Data Visualization:

## STEP 1:

Sales trend over time using the line chart

• I clicked on the Month name and Sales column and dragged it to the desired 
position

![Visual-1](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/4243d74b-ae45-4cb3-828b-b8daeb6a567c)

• To create a Chronological order for the months, I followed these steps:
1. I selected the column containing the months.
2. I navigated to the "Column Tools" and choose "Sort Column."
3. I selected "Sort by Month Number" to sort the months in 
chronological order

![Visual-1a](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/45736964-1dd2-46f1-8465-87b550ab36d0)


## STEP 2: Best selling products using tree map
• To edit theme for background color and font size, I accessed the "Format" option for the visualization and adjust the settings as desired.

![Visual-2](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/65b37d12-f23a-44ba-8a7b-3e58dcbef67a)

## STEP 3: Top 5 best selling product using stacked bar chart
1. To manipulate the visualization, I performed the following steps:
•  I dragged and dropped the "Product" into the Y-axis.
•  I placed the "Quantity" into the X-axis for appropriate ordering

![Visual-3](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/fa9e0076-3e83-4af3-956a-bd8965e5deda)

## STEP 4: Top 5 cities by sales using map

![Visual-4](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/450b9d36-b16a-481b-afd0-5e65f251f414)


## STEP 5: Weekly sales distribution by weekday using column chart

![Visual-5](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/bba39783-764f-4b6b-82f7-a5290fa2318d)


## STEP 6: Slicer is used to make this kind of visual
• To create a slicer visualization, I dragged and dropped the "Month Name" field 
into the slicer option. 
- To display the slicer in a vertical list, I accessed the 
slicer settings and choose the option for a vertical column layout.

![Visual-6](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/e254dfd4-0562-4cb9-a172-fd23e383e6ae)


## STEP 7: To find the revenue metrics:
• Total profit: I summed up the net profit from all sales transactions.
• Sales quantity: I calculated the total number of units sold.
• Profit margin: I computed the ratio of net profit to total revenue, usually 
expressed as a percentage.

***N.B:*** REVENUE = SUM OF SALES. 
This is done by following the steps below:
1. I selected the "Card" visualization type, then dragged and dropped the "Sales" 
into the designated field. I converted it to the "SUM" aggregation. 
2. Additionally, I adjusted the display units to show values in millions, 
billions, trillions, or hundreds, and customize the number of decimal 
places as needed.



![Visual-7](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/9df9d09a-bbc0-410b-931f-1aa5148bf2f8)

Sales quantity 
• I selected the "Card" visual, then dragged and dropped the "Quantity 
Ordered" int the designated field. 
• I accessed the "Format" option for the visual, and adjusted the callout 
value to change the display unit of the quantity ordered as desired.

![Visual-7a](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/1af9a5fe-db48-43b1-b79c-96e29c9cf220)


• Furthermore, I clicked on new measure, then; 
 
• Find the total cost by using the new measure 
• Find the total sales by using the new measure
• Find the profit margin by using this formula in the measure.
• Choose the measure created and placed it in the card visual and designed it 
using the “Format visual


![Visual-7b](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/b23b52d0-fedc-4c62-a0cf-75551ae03364)



## Data Analysis and Visualization:

Several expressions and functions were made to arrive at the desired KPI or Metrics.
I arrived at a report with a single dashboard consisting of different visuals such as bar chart, doughnut chart, line chart, slicer, and KPIs, giving the summary of the insights gained into the company's performance.

## Features of the Report:
The dashboard conveys information about the following key areas:
- QUANTITY OF PRODUCTS ORDERED
- TOTAL REVENUE
- PROFIT MARGIN
- KEY CUSTOMERS
- TOP-SELLING PRODUCTS
- SALES TRENDS

![Screenshot 2024-01-06 050336](https://github.com/RemedyData/Meriskill_Skill_Sales_Analysis_Internship/assets/137626163/7f9a58a5-1a34-497b-8ce5-dadd45992e27)


## Analysis

Summary of the insights gained into the company's performance: 

▪︎A total revenue of £34,492,000 was realized within the year 2019.

▪︎With about 21 products which was in stock, 209,000 orders were received within the year 2019 generating a profit margin of 53.83% .

▪︎USB-C Charging Cable got the highest demand rate of 23,975. While Macbook Pro Laptop happens to be the product with the most generating returns of £8,037,600. iphone competed with Macbook Pro Laptop with a difference of £3,243,300. 

▪︎Highest revenue of £4,613,443.34 was made in December,  within the year 2019.

▪︎Lowest revenue of £1,822,256.73 was made in January, within the year 2019.

▪︎USA happens to be the country with the highest revenue. 


## Recommendation

- There are no doubts that the business is performing well as there are potential leads within the company yielding higher returns.

- More advertisements in form of placards, television spots and print publications should be done in the month of December as more sales is being made in this month.
  
- Directing more sales to USA happens to be a gold mine for the company.

- Based on the analysis of the Customers-purchasing pattern, It is suggested that USB-Charging Cables should be made available for sales at all time due to its high demand.

- It is suggested that more capital be invested in the sales of Macbook Pro Laptop alongside with iphone so as increase the company's leverage. 


---

### Thank you for reading.

I am open for entry-level data analyst role.
