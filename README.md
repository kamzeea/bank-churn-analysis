# Bank Churn Analysis

## Overview
A churn analysis was done to understand why a bank's customers leave across age groups, country, and balance tiers.

## Business Question
Which customer segments are most at risk of churning, and what factors are associated with higher churn rates?

## Dataset
- 4,999 bank customers
- 12 variables
- Sourced from Kaggle

## Key Findings and Recommendations
In our exploration we found various factors related to churn rate. The ones we determined had the largest impact were Country, Age, and Balance.

**Age:** We looked at the churn rate across 7 age groups — 20s, 30s, 40s, 50s, 60s, 70s, 80s. The highest churn was among customers in their 50s, with the lowest among customers in their 20s and 80s. Age matters because it indirectly reflects what stage of life customers are in. People in their 50s are nearing retirement, which brings needs for retirement planning and wealth management. We need to make them aware that we have products to meet those needs before they seek them elsewhere.

**Country:** We have presence across three countries — France, Germany, and Spain. Germany had the highest churn rate (31.39%), roughly double that of France (17.44%) and Spain (17.37%). This suggests something is wrong in Germany specifically. The bank needs to understand the cultural differences, market landscape, and tailor products and retention strategies to the banking culture of each country.

**Balance Tiers:** We bucketed balances into tiers and examined their churn rates — Low (16.00%), Middle (17.37%), Upper (25.37%), High (22.74%). Customers in the upper tier had the highest churn rate, which contradicts our initial hypothesis that the highest earners are most likely to churn. We need to evaluate what stage these customers are in their lives and ensure they are satisfied with our offerings, given their significant investment in our products.

## Tools Used
- Python (Pandas, SQLite3)
- SQL
- Power BI 

## Dashboard
View the interactive Power BI dashboard here:
https://app.powerbi.com/groups/me/reports/cec8d2c7-df94-4c61-a396-1ef609752e3a/40a2715f9c9bb2efd4fe?experience=power-bi

## Project Structure
- `exploration.ipynb` — data loading, cleaning, SQL analysis
- `data/` — CSV files
- `churn_analysis.sql` — SQL queries

## Author
Chikamso Ezeaku