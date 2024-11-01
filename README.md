# Drug Sales Dashboard

## Table of Content
---
 - [Project Overview](#project-overview)
 - [Data Source](#data-source)
 - [Data Cleaning/Preparation](#data-cleaning/preparation)
 - [Data Modelling](#data-modelling}
 - [Exploratory Data Analysis](#exploratory-data-analysis)
 - [Data Analysis](#data-exploratory)
   
## Project Overview
---
This project aims to analyze drug sales data by merging a fact table with customer and drug lookup tables. The analysis will provide insights into customer behavior, sales performance, and product profitability. The Analysis aims to help drug sales distribution and optimisation of the drug inventory and marketing strategies to determine the most profitability products.
<img width="613" alt="Drug Dashboard" src="https://github.com/user-attachments/assets/b80057a2-d6ea-48fc-b5e0-c18144b7dbc4">

The Objective of this project is to analyse the sales analysis of drugs sold during the period and to determine the best sales country, gender, period of the year
## Data Sources
---
The data used in this project comes from three main tables:
1.	Customer Table: Contains customer demographics and additional info.
2.	Drug Lookup Table: Lists drug details, including sales price and treatment information.
3.	Fact Table (Sales Data): Records sales transactions, linking customers to drugs sold.

## Tools
---
Excel
Power Bi

## Data Cleaning/Preparation
---
Data Cleaning/Preparation
The data was cleaned and prepared as follows:
•	Duplicate Entries: Removed duplicate customers based on CustomerID and ensured unique DrugID in the drug lookup table.
•	Data Types: Converted SaleDate to date format and ensured numerical fields like UnitsSold were of the correct type.
•	Missing Values: Addressed any missing values through imputation or removal where necessary.
•	Merging Tables: Merged the three tables on relevant keys:
•	CustomerID from the Customer Table to link with the Sales Data.
•	DrugID from the Drug Lookup Table to link with the Sales Data.
- Power Query: Power QUERY WILL BE USED  for data extraction
  
## Data Modelling
---
The final merged dataset contains the following columns:
•	CustomerID: Unique identifier for each customer.
•	FirstName, LastName, Age, Gender, Country, OtherCustomerInfo: Customer details.
•	DrugID: Unique identifier for each drug.
•	DrugName, UnitSalesPrice, CostOfProduction, Treats: Drug details.
•	SaleID, UnitsSold, SaleDate, BuyerType: Sales transaction details.


## Exploratory Data Analysis
---
Initial analysis was performed to identify trends and patterns:
•	Customer Segmentation: Analyzed customer demographics to identify key segments (e.g., age, gender).
•	Sales Trends: Evaluated sales performance over time, identifying peak sale periods.
•	Product Performance: Assessed which drugs generated the most revenue and had the highest sales volume.
### Data Analysis
The analysis revealed several insights:
•	Top Customers: Identified top customers by total sales volume.
•	Most Profitable Drugs: Analyzed drugs with the highest profit margins (Unit Sales Price - Cost of Production).
•	Sales by Customer Type: Compared sales performance between different buyer types (e.g., Seller vs. User).
### Example Insights
1.	Customer Trends: Frequent buyers aged 50-70 showed the highest purchase frequency.
2.	Product Trends: Amoxicillin and Ibuprofen were among the top-selling drugs.
3.	Sales Peaks: Notable increases in sales were observed during specific months, potentially linked to seasonal health trends





