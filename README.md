# Forggith-Pharmaceuticals-Report
![](Logo.png)
---
## Introduction
This project is a task carried out during my one month Power BI Developer internship with **Foresight BI & Analytics**. It is a report for a pharmaceutical company called **Forggith Pharmaceuticals**. Forggith Pharmaceuticals (Forggith) is a Pharmaceutical Manufacturing company based in Germany. As a Manufacturing company, they produce medical drugs that get to consumers through their Distributors. This project is to analyze and derive insights into performance of different sectors by various categories and time periods. It is to help the Sales Representatives track their performances throughout the period to plan their marketing activities. It is also to assist the Team Managers in tracking their teams' performances throughout the periods to plan their teams' activities, and it is also for the Executive team to use to be able to track Revenue numbers to monitor alignment with the set targets to influence medium- to long-term strategies.
## Problem Statement
### Sales Performance ###
1. Total  Revenue
2. Total Revenue Year To Date (YTD)
3. Total Revenue Previous Year YTD
4. Total Revenue Same Period Last Year(SPLY)
5. Total Target
6. Total TargetYTD
7. Actual Revenue Performance Previous Year YTD vs Target Previous Year YTD
8. Actual Revenue Performance YTD vs Target YTD
9. Revenue Month on Month Percentage Change
10. Revenue Distribution by Location
11. Revenue by Channel
12. Revenue by Product Class
### Marketing Performance ###
1. Revenue Achieved vs Revenue Target
2. Volume Achieved vs Volume Target
3. Actual Revenue by Sales Representative
4. Target Revenue Achievement% by Sales Representative
5. Actual Volume by Sales Representative
6. Target Volume Achievement by Sales Representative
7. Actual Revenue Achievement by Sales Team
8. Revenue and Volume Achievement by Product.
## Skills/Concepts Demonstrated
The following Power BI features were incorporated:
- Power Query for transformation
- Bookmarking
- DAX
- Quick measures
- Page navigation
- Modelling
- Filters
- Tooltips
- Button
## Data Sourcing
The data was sourced from the **Foresight BI & Analytics** team since it was an internship program. 

Forggith-Pharmaceuticals-Report database tables - PharmDatasets and PharmTargets
The following tables were selected from the dataset to be used for the analysis
1. Channel Table
2. Employees Table
3. Location Table
4. Products Table
5. Sales Table
6. Subchannel Table
7. Targets Table
### PharmDatasets
![](Sales_Table.png) 
### PharmTargets
![](Target_Table.png)

## Data Transformation
- For all the tables, the first rows were changed to become Headers.
- In the Sales Table, the data type for the "MonthYear" column was changed to Date. I also appended queries for the "2023-2025" sales table to the "2022" sales table and named it "Sales"
![](Sales_Appended.png)

- In the Targets Table, I unpivoted the year columns, then I merged the month and the year column together. I also changed the data type to Date and renamed it as "Date"
![](Target_Unpivot.png)

## Data Modelling
Automatically derived relationships are adjusted to remove and replace unwanted relationships with the required.

Adjusted Model          |           Auto-model
:----------------------:|:----------------------:
![](Adjusted_Model.png) |  ![](Auto-model.png)

The model is a star schema.
There are 5-dimension tables and 2 fact tables. The dimension tables are all joined to the fact tables with a many-to-one relationship.

## Visualization
The report comprises of 3 pages:
1. Overview (Home)
2. Sales Report
3. Marketing Report

You can interact with the report [here](https://app.powerbi.com/view?r=eyJrIjoiNGY1MTkzNTUtM2UwNi00NmNmLTg5M2MtMzFjNDc0YTg4YjI0IiwidCI6IjVkMmExNjk0LWNiNzAtNDJlYi04MmNhLTRmMjBlMWMyODFmMSJ9)

I also incorporated tooltips for better insights.
![](Tooltip.png)

## Analysis
### Overview/Home Page: 
![](Home.png)

- Has a Date filter that filters through 2022 - 2025.
- The three tabs at the top are buttons with hovering effects and each navigates through to the pages with similar name.
- Total of 27 million products were sold.
- Total revenue generated was $11.12 billion 💰
- Total target was $8.45 billion.
### Sales Report Page:
![](Sales_Report.png)

- This page is sliced by Team, Year, Quarter and Month 🗓️
- There are 4 KPI cards diplaying Total Target, Total Products, Volume Sold vs Target Volume and Total Revenue vs Target.
- There are charts displaying Revenue by Product class, Revenue by Channel, Revenue distribution by City, Revenue month on month % change and Revenue vs Target PYTD.
- There are 240 products in total.
### Marketing Report Page: 
![](Marketing_Report.png)

- This page is sliced by Product Category, Team, Year, Quarter and Month 🗓️
- There are 4 KPI cards diplaying Total Customers, Total Distributors, Volume Sold vs Target Volume and Total Revenue vs Target.
- There are charts displaying Top and Bottom % products by Perfomance, Revenue Performancve by Team and also Performance by Sales Representatives. 
- There are 551 Customers in total 🧑‍🤝‍🧑
- There are 16 Distributors in total.
 
## Conclusion / Insights
- The Analgesics Product Class yielded the highest revenue of $2.2bn while the Antimalarial class yielded the lowest revenue of $1.4bn.
- Ionclotide drug yielded the highest revenue of $262k as product sold while Diaxolol yielded the lowest of $72K in total.
- 2023 gave the highest revenue of about $0.9bn when compared to its yearly target as against other years.
- Distribution/Sales to Pharmacies yielded more revenue of 52.9% as compared to that of the Hospital channel.
- The Delta team showed highest performance in all years generating a total revenue of $3.43bn 👍 while the Alfa team showd lowest performance of $2.42bn.
- In 2022, Anne Wu performed best. In 2023, Abigail Thompson perfomed best. In 2024, Jimmy Grey performed best and in 2025, Stella Given performed best. Overall, Abigail Thompson yielded the most revenue of $929.43m ✨

## Recommendation
- I recommend expanding distribution and sales beyond Europe, as this will favour sales of other classes more, especially the antimalarial drugs.
- Best performing teams should be given higher bonuses as this will make other teams perform better in future years to come.
- Sales Representatives seen to be performing well should be also be given bonuses, or better still have their salaries increased and should also be considered for promotions.

![](Thank_you.jfif)



