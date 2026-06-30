# Used-Cars-Market-Analysis
This project analyzes a used car dataset to uncover the key factors affecting resale prices and understand market trends. The analysis is performed using Python for data cleaning and MySQL for exploratory data analysis (EDA).  

# Business Problem
The used car market consists of vehicles with different prices influenced by several factors such as brand, manufacturing year, fuel type, ownership history, seller type, and kilometers driven.

This project answers important business questions, including:  
Which brands dominate the used car market?  
Which brands have the highest resale value?  
What are the most and least expensive cars?  
Which seller type lists the most vehicles?  
How does vehicle age influence resale prices?

# Tools & Technologies  
Python  
Pandas  
MySQL

# Dataset  
Source: CarDekho Used Cars Dataset

# Dataset Features  
Car Name  
Brand Name  
Manufacturing Year  
Vehicle Age  
Selling Price  
Kilometers Driven  
Fuel Type  
Seller Type  
Transmission  
Owner

# Data Cleaning (Python)
  
Cleaning Steps  
Imported the raw CSV dataset  
Removed duplicate records  
Checked for missing values  
Verified data types  
Standardized column names  
Created Brand_Name from the car name  
Created Vehicle_Age using the manufacturing year  
Exported the cleaned dataset for SQL analysis

# Exploratory Data Analysis (MySQL)  
The following business questions were answered using SQL.
  
Dataset Overview  
Total number of used cars  
Number of unique brands  
Average selling price  
Price Analysis  
Least expensive car  
Most expensive car    
Top 10 most expensive cars  
Brand Analysis  
Brand with the highest number of listings  
Top 10 brands by average resale price  
Top 10 brands by sales volume  
Fuel Analysi  
Most popular fuel type  
Average resale price by fuel type  
Seller Analysis  
Seller type with the highest number of listings  
Owner Analysis  
Average selling price by owner category  
Vehicle Analysis  
Average vehicle age  
Highest mileage vehicles

# Key Insights  
The dataset contains a diverse range of used cars from multiple automobile brands.  
A small number of brands account for the majority of vehicle listings, indicating strong market presence.  
Premium brands achieve significantly higher average resale prices than economy brands.  
Petrol and Diesel vehicles dominate the used car market, while CNG, LPG, and Electric vehicles make up a smaller share.  
Seller type analysis highlights the distribution of listings between dealerships and individual sellers.  
Cars with first owners generally retain higher resale value.  
Older vehicles typically sell for lower prices, reflecting normal depreciation.  
Vehicles with very high mileage are generally listed at lower selling prices than those with lower mileage.

# Skills Demonstrated  
Data Cleaning using Python (Pandas)  
Feature Engineering  
SQL Data Analysis  
Aggregate Functions  
GROUP BY & ORDER BY  
Filtering & Sorting  
UNION & Subqueries  
Business Insight Generation  
Data Storytelling
