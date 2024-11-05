# Customer-Segmentation-Analysis-for-a-Subscription-Service
---


## Overview
---
This project analyzes customer data for a subscription service to identify segments and trends. The goal is to understand customer behavior, track subscription types and identify key trends in cancellations and renewals.


## Data Sources
---
The dataset from the subscription service includes key columns:

1. Customer ID and names
2. Region
3. Subscription type
4. Subscription start and end dates
5. Cancellations
6. Revenue


## Project Objectives
---
- Total Revenue
- Average Revenue
- Number of Subscribers
- Total Revenue by Region
- Most popular subscription types
- Total revenue by subscription type
- Total revenue by subscription type
- Total Revenue by Subscription Type
- Total number of customers from each region
- Total number of customers from each region
- Most popular subscription type by the number of customers


## Tools Used
---

i. Ms Excel [Download Here](https://www.microsoft.com/en-us/microsoft-365/excel) for data cleaning, analysis and visualisation.

ii. SQL [Download Here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) for quering of data.

iii. Power BI [Download Here](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads) for creating visualisations with filters.


## Tasks executed with Tools Used
---

i. Ms Excel
- Data cleaning and formatting using functions Sum, Count, Avg.
- Calculating subscription duration and other variables
- Created pivot tables, dashboards and reports with filters

          
 ii. SQL
 - Querying of data with functions -
 
 ```SQL
select sum (Revenue) as TotalRevenue from [dbo].[LITA Capstone Dataset - CUSTOMER DATA - Copy]

select avg (Revenue) as AverageRevenue from [dbo].[LITA Capstone Dataset - CUSTOMER DATA - Copy]

select avg (Subscription_Duration) as AverageSubscription_Duration from [dbo].[LITA Capstone Dataset - CUSTOMER DATA - Copy]
```


iii. Power BI
- Connected to data
- Added data sources
- Created visualisations, dashboards and reports with filters


## Data Visualizations
