# Customer Segmentation
## Table of Contents
 - [Project Overview](#project-overview)
 - [Data Sources](#data-sources)
 - [Tool](#tool)
 - [Data Preparation](#data-preparation)
 - [Exploratory Data Analysis](#exploratory-data-analysis)
 - [Data Analysis](#data-analysis)
 - [Results](#results)
 - [Recommendation](#recommendation)
 - [Limitation](#limitation)


### Project Overview 

I worked on a Customer Segmentation Dashboard for an imaginary bank called Nova.The goal was to analyze customer behavior and group them into meaningful segments to support better decision-making. Using Excel, I explored customer by generation, customer loyalty segmentation, customer wealth profile, customer growth timeline and professional profile of customer base to create a simple, interactive dashboard.

![Dashboard](dashboard PNG)

![photo_2025-11-19_12-57-23](https://github.com/user-attachments/assets/fa640833-7361-4c71-a84e-f18ec80fe791)

### Data Sources

Customer Data:The primary dataset used for this analysis is the "customers_data.csv" file, containing detailed information about each customer that patronise the company.

### Tool
 - Excel - Data Cleaning, Data Analysis
   - [Download here](http://microsoft.com)
 - PivotTables for aggregation
 - PivotCharts (bar, donut, line)
 - Slicers 
     

   ### Data Preparation

   In the intial data preparation phrase, we performed the following tasks:
   1. Data loading and inspectation.
   2. Removed duplicates
   3. Formatted dates, income values
   4. Created calculated fields
 


### Exploratory Data Analysis 

EDA involved exploring the customers data to answer key questions, such as:
 - Who their customers are?
 - Who their customer are by tenure?
 - Their customer growth?
 - Their customer occupation?
 - Who their customer are by age group?
 - Who their customr by income bracket
   
   ### Data Analysis

   Include some interesting code/feature worked with

```power query
If income <= 100000 then Low
If income <= 150000 then Medium
If income <= 300000 then High
Else Premium
```

### Results

1. A large portion of customers fall under the Low income segment
2. The majority of customers are in the boomers age group, which represents the bank's most active customer base

### Recommendation
Based on the analysis, we recommend the following actions:
 - Develop Tailored Marketing Campaigns by Income Group
 - Strengthen Digital Banking for Younger Customers
 - Increase Retention Programs for High-Value Customers
 - Provide Financial Education for boomer age group Customers
 - Use Segmentation to Improve Revenue Forecasting
2
### Limitation
- Limited Variables for Segmentation
- Basic Conditional Logic
- No Temporal Analysis
- Static Dashboard Environment

😄
💻

`Column_1`
