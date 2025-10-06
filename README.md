## Brunto-Electronics-Performance-Sales-Dashboard

This project is a dynamic Sales Performance Dashboard for Brunto Electronic, Built using Microsoft Power BI. My objective was to transform the raw sales dataset into a proffessional dashboard that helps stakeholders, like sales manager monitor key performance indicators(KPIs) and make business decisions.


## 📌Project Overview
This project is a multi-faceted Sales and Customer Analytics Dashboard for Brunto Electronics, built using Microsoft Power Bi. The primary objectives was to transform raw sales and customer data into a dynamic and professional dashboard to help stakeholders monitor  key performance indicators (KPIs), analyze regional performance, and make data driven decisions. The project is a composed of two interconnected dashboards that provide a comprehensive overview of sales performance from different andles.
## Dashboard 1:Brunto Electronic Sales Performance Dashboard
<img width="611" height="338" alt="BRUNTO DASHBOARD" src="https://github.com/user-attachments/assets/f653b8d2-2a14-494f-9333-f181496e9af8" />

## ✨**Key Features**
-	**KPIS**: The dashboard prominently  displays a set of key performance indicators (KPIS) I calculated, including Total Sales, Maximum Sales, Average Sales, Minimum Sales, and Sales Percentage.
-	**Salesperson Performance**: I created a visuals that shows Total Sales by Salesman, allowing for a quick comparison of individual performance.
-	**Product Analysis**: I created visuals to analyze product performance including Average Sales by items, Maximum Sales by items, and Minimum Sales by items.
-	**Goal Tracking**: A gauge chart is used to visualize the Percentage of Sales, providing a clear way to rack progress towards sales goal.


## 🛠️**Methodology**
My methodology for this project was methodical to ensure accuracy and clarity.
-	**Data Acquisition and Cleaning**: I began by importing the raw sales dataset into my power BI Power Query Editor. I then performed essential data cleaning steps, correcting data types, and ensuring data consistency in my data.
-	**Data Modelling**: I structured the data model by ensuring all tables are related correctly, allowing for seamless filtering and analysis across the dashboard.
-	**DAX Calculations**: I used DAX (Data Analysis Expressions) to create all the custom measures for my KPIS, such as Average Sales and Sales Percentage.
-	**Dashboard Design**: I designed a clean and professional dashboard, placing KPIs prominently at the top for quick reference. The visuals were chosen carefully to best represent the data and tell a clear story about the sales performance.

## 🗂️**Data Structure**:
The raw data is a single, flat file containing a comprehensive record of sales transactions for Brunto Electronics.  It is organized onto columns and rows, making it suitable for  direct analysis in Power BI. The key fields in the dataset includes:

-	**Order Information**: Order Date, and Total Order
-	**Product Information**:  Items, Items Name.
-	**Sales Metrics**: Total Sale, Units, Quantity
-	**Sales Person Information**: Sales man name, and Manager

## 🛠️**Workflow**
-	**Data Ingestion**: I imported the raw data into Power BI.
-	**Data Transformation**: I used Power Query to clean and transform the data.
-	**Measure Creations**: I wrote DAX formulas  to create the necessary metrics ( Total Sales, Average Sales, etc.).
-	**Visualization**: I created charts and visuals including the gauge chart for sales percentage.
-	**Dashboard Finalization**: I arranged all the visuals on a single page to create the final, interactive dashboard


## 📈**Key Findings**
Based on my analysis, here are some of my key findings from the Brunto Electronic Sales Dashboard.
-	**Top Performers**: The dashboard quickly identifies the top performing salespersons based on their Total Sales.
-	**Product Performance**: I was able to pinpoint the items with the highest and lowest average and maximum sales, providing insights into which products are selling well.
-	**Sales Goal Tracking**: The sales percentage gauge chart provide a real time view of whether the team is on track to meet its sell targets.


## 🚀**Skills Demonstrated**
-	**Power BI**: I demonstrated expertise in all aspects of power Bi, from data loading to data publication.
-	**DAX (Data Analysis Expressions)**: I used DAX to create custom measures for key metrics.
-	**Power Query** : I utilized power Query for efficient data cleaning and transformation.
-	**Data Visualization**: I designed a professional and stakeholder friendly dashboard using a variety of charts to present data in an impactful way.


## 💡**Recommendations**
Based on my insights, I would recommend the following actions should be taking:
1.	**Acknowledge Top Salespersons**:  the data should be use to recognize and reward top performers to encourage continued high performance.
2.	**Analyze Product Mix**: There should be an investigation on why certain items have high maximum  sales but low average sales to optimize product offering and pricing.
3.	**Monitor Progress**:  The dashboard should be used regularly to monitor the sales percentage and make adjustment to strategies as  needed to meet sales goals.


## Dashboard 2: Brunto Sales Performance by Sales Man and Manager Across Regions
## 📌**Project Overview**
This dash board provides a detailed breakdown of sales performance across different regions, managers, and salespeople.

## ✨**Key Features**
-	**Regional Performance**: The dashboard features separate analyses for different regions, including a dedicated visual for Unit Sold by West and items and Unit Sold by East and items.
-	**KPIs**: I calculated key performance indicators (KPIs) for each region, including Unit sold by West, Unit Sold by Central, and identified the Region with the Maximum Sales which is (West) and the Region with the Average Sales which is the (Central).
-	**Product Analytics**: The dashboard identifies the best selling items, which is the Video Games, and display visuals to show product performance across regions.
-	**Interactive Slicers**:  I included interactive slicers for Manager and Order Dates to allow users to filter the data and analyze sales performance for specific managers or time periods.
-	**Goal Tracking**: A gauge chart is used to track the Unit Sold by West, providing clear visual representation of progress toward a sales goal.
-	**Sales and Manager Tracking**: I used a table chart that provides a detailed view of Order Dates, Salesman, and Manager, ensuring accountability and a clear link between performance and personnel.

## Dashboard Preview
<img width="612" height="343" alt="LINK4" src="https://github.com/user-attachments/assets/dcd3c16c-a964-458d-8f64-87a23d337743" />

## 📈**Key Findings**
-	The West Region consistently shows the highest sales, which suggests it is a key growth driver for the company.
-	The Central Region has a strong and consistent average sales performance, indicating a stable market.
-	Video Games are the best selling item, providing a clear insights into popular product categories.
-	The manager slicer allows for a quick identification of top performing managers and their respective teams performance.

## 🛠️**Methodology**
My methodology for this product was methodical to ensure accuracy and clarity.
1.	**Data Acquisition and Cleaning**: I began by importing the raw sales data into Power Bi Power Query Editor. I then performed essential data cleaning steps, including handling missing values, correcting data types, and ensuring data consistency for my analysis.
2.	**Data Modelling**: I structured the data model by creating relationships between tables, which allowed for seamless filtering and analysis across the dashboard .
3.	**DAX Calculations**: I used DAX (Data Analysis Expressions) to create all the custom measures for my KPIs, such as Average Sales and Unit Sold by West.
4.	**Dashboard Design**: I designed professional, single page dashboard to consolidate all the key metrics and visuals, ensuring they were both aesthetically pleasing and easy to navigate.


## 🗂️**Data Structure**
The raw data is a single, flat file containing record of sales transactions for Brunto Electronics. It is organized into rows and columns, making it suitable for direct analysis in Power BI. The key fields in the dataset includes:
-	**Order Information**: Order Date
-	**Product Information**: Item Name
-	**Sales Metrics**: Sales, Quantity, Unit Sold, and Total profit
-	**Geographic Information**: Region
-	**Salesperson Information**: Salesman, Name, Manager Name.

## 🛠️**Workflow**
1.	**Data Ingestion**: I imported the raw data into Power Bi.
2.	**Data Transformation**: I used Power Query to clean and prepare data for analysis
3.	**Measure Creation**: I wrote DAX formulas to create the necessary metrics which include (Total Sales, Average Sales, etc.)
4.	**Visualization**: I created a variety of charts and visuals to present the data effectively, including bar charts, a gauge chart, and a detailed table.
5.	**Dashboard Finalization**: I arranged all the visuals and slicers on a single page to create the final, interactive dashboards.

## 🚀**Skills Demonstrated**
-	**Power BI**: I demonstrated expertise in all aspects of Power BI, from data loading to report publication.
-	**DAX (Data Analysis Expressions)**: I used DAX to create custom measures for key metrics
-	**Power Query**: I utilized Power Query  for efficient data cleaning and transformation.
-	**Data Visualization**: I designed a professional and story telling dashboard using variety of charts to present data in an impactful way.
-	**Business Intelligence**: I demonstrated my ability to turn raw data into actionable business insights.


##  💡**Recommendations**
Based on these insights, I would recommend the following actions should be taking:
1.	**Replicate West Success**: There should be study of sales strategies and marketing efforts in the west region and apply them on other regions to boost their performance.
2.	**Focus on Best Selling Items**: Highlight video games in marketing campaigns and ensure a steady inventory to capitalize on their popularity.
3.	**Utilize the Dashboard**: The managers should regularly use the dashboard to monitor their teams performance and provide targeted coaching to improve sales in some of the underperforming areas and regions.


