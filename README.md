# Customer-Segmentation-Analysis-for-a-Subscription-Service
---


## Overview
---
This project analyzes customer data for a subscription service to identify segments and trends. The goal is to understand customer behavior, track subscription types and identify key trends in cancellations and renewals.


[Overview](#overview)

[Data Sources](#data-sources)

[Project Objectives](#project-objectives)

[Tools Used](#tools-used)

[Tasks executed with Tools Used](#tasks-executed-with-tools-used)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data visualizations](#data-visualizations)


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


## Exploratory Data Analysis
---

This involved the exploring of the data to answer questions like -
- Total Revenue
- Most popular subscription types
- Total Revenue by Subscription Type


## Data Visualizations
---

![Average Subscription Duration, SQL](https://github.com/user-attachments/assets/c91ea75f-d949-41d5-9e37-f27d2749af55)

![Average Subscription Duration](https://github.com/user-attachments/assets/259f3328-354f-4d4a-bbc5-6b7e2c9cf99a)

![Average, Revenue](https://github.com/user-attachments/assets/b92547bf-67cf-418a-a065-894d3fe9df97)

![CUSTOMER DATA USING EXCEL FORMULA](https://github.com/user-attachments/assets/be2638c6-138d-4eca-b55b-53e2a1a782e6)

![Most Popular Subscription Type](https://github.com/user-attachments/assets/e5b12bcc-43b6-444e-8077-1cd206be4d0b)

![Pivot Tables](https://github.com/user-attachments/assets/c99da610-cac7-4190-a772-05668edb3ee2)

![Report Dashboard with Slicer](https://github.com/user-attachments/assets/1b9edb0d-3e7d-4852-a959-4e639e3d36e5)

![Subscription Type and Region, East and West](https://github.com/user-attachments/assets/73475432-5af1-4dc8-8ff1-17227eda08c5)

![Subscription Type and Region, North and South](https://github.com/user-attachments/assets/87746780-5522-45f9-a24d-f040f6975178)

![Total Number of Active subscriptions](https://github.com/user-attachments/assets/d2570fe7-7637-469d-ba2e-6825413eea41)

![Total Number of Cancelled subscriptions](https://github.com/user-attachments/assets/89fe7f16-f19a-4493-8de9-461b8d85adaf)

![Total Number of Customers, East Region](https://github.com/user-attachments/assets/a6b3ea70-fdae-46e1-872f-4e3f04e93cb2)

![Total Number of Customers, North Region](https://github.com/user-attachments/assets/1a5cc80d-14e1-489f-a8ad-73aeca12b200)

![Total Number of Customers, South Region](https://github.com/user-attachments/assets/b05d273d-c591-4818-802b-e68217eeee39)

![Total Number of Customers, West Region](https://github.com/user-attachments/assets/75c1558a-691e-438a-80b0-fb1aa34d3d54)

![TOTAL REVENUE BY REGION, CUSTOMER DATA](https://github.com/user-attachments/assets/c7ebea3b-a647-40f4-beae-1af7b7fa15ce)

![Total Revenue by Subscription type, Basic](https://github.com/user-attachments/assets/bcf153d1-8d8e-42de-bb97-ce91c5de1f7e)

![Total Revenue by Subscription type, Premium](https://github.com/user-attachments/assets/891558d6-d61e-4ab5-8d0c-d03acd39ed89)

![Total Revenue by Subscription type, Standard](https://github.com/user-attachments/assets/a2ab73d7-ab33-4839-97fb-1ccd7680dee7)

![Total Revenue by Subscription type](https://github.com/user-attachments/assets/e0ceed30-ae0c-4b9a-b4ca-264bf66b89fa)

![Total Sum, Revenue](https://github.com/user-attachments/assets/dd20cf89-7de1-47c6-a7f7-e6bb4375dcbc)

![Customer Segmentation and Subscription Service Analysis](https://github.com/user-attachments/assets/e0591d12-d3c6-48c6-8b28-23820f1e5069)

