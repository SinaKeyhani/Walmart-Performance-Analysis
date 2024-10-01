# Walmart Performance Analysis

<p align="center">
<img src="https://github.com/SinaKeyhani/Stock_analysis/blob/main/close-up-of-stock-market-data-on-digital-display-1058454392-c48e2501742f4c21ad57c25d6a087bd0.jpg" alt="Project Image" width="500" height="400"/>
</p>



## Table Of Contents
* Introduction

* Dataset Description

* Recommended Analysis

* Approach

* List of Questions

* Relevant Insights

* Relevant Links

## Introduction
In the scope of this project, our objective is to delve into the Walmart Sales data, investigating the performance of key branches and products, analyzing sales trends across various product categories, and examining customer behavior. The primary goal is to gain insights into potential enhancements and optimizations for sales strategies.

## Dataset Description
In this recruiting competition, job-seekers are provided with historical sales data for 45 Walmart stores located in different regions.

Each store contains many departments, and participants must project the sales for each department in each store. To add to the challenge, selected holiday markdown events are included in the dataset.

These markdowns are known to affect sales, but it is challenging to predict which departments are affected and the extent of the impact.

This dataset contains 4 files, in CSV format:

stores.csv - This file contains anonymized information about the 45 stores, indicating the type and size of store.

train.csv - This is the historical training data, which covers to 2010-02-05 to 2012-11-01. Within this file you will find the following fields:

Store - the store number

Dept - the department number

Date - the week

Weekly_Sales - sales for the given department in the given store

IsHoliday - whether the week is a special holiday week

test.csv - This file is identical to train.csv, except we have withheld the weekly sales. You must predict the sales for each triplet of store, department, and date in this file.

features.csv - This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:

Store - the store number

Date - the week

Temperature - average temperature in the region

Fuel_Price - cost of fuel in the region

MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.

CPI - the consumer price index

Unemployment - the unemployment rate

IsHoliday - whether the week is a special holiday week

## Recommended Analysis
1. Product Analysis - Perform an in-depth analysis of the data to gain insights into various product lines, identify top-performing product lines, and pinpoint areas where improvement is needed for specific product lines.

2. Sales Analysis - The objective of this analysis is to explore the sales trends of products, providing valuable insights into the effectiveness of each applied sales strategy. The findings will guide us in identifying necessary modifications to enhance sales performance.

3. Customer Analysis - The purpose of this analysis is to reveal distinct customer segments, identify purchasing trends, and assess the profitability associated with each customer segment.

## Approach
Data Preparation :

* The initial step involves scrutinizing the data to identify and address NULL or missing values.

* A database is built, tables are created, and data is inserted into the database.

* Setting each field as NOT NULL during table creation ensures the absence of NULL values.

Feature Engineering : 

* New columns are generated from existing ones to enhance the dataset.

* The "time_of_day" column categorizes sales into Morning, Afternoon, and Evening, providing insights into peak sales periods.

* The "day_name" column captures the day of the week for each transaction (Mon, Tue, Wed, Thur, Fri), aiding in identifying the busiest days for each branch.

The "month_name" column highlights the month of the year for each transaction (Jan, Feb, Mar), facilitating the analysis of monthly sales and profits.

* Exploratory Data Analysis (EDA) : 

The EDA process is undertaken to address the specified questions and achieve the outlined objectives in this project.

## List of Questions
### A. Generic Questions

How many unique cities does the data have?

In which city is each branch?

### B. Product-related questions
How many unique product lines does the data have?

What is the most common payment method?

What is the most selling product line?

What is the total revenue by month?

What month had the largest COGS?

What product line had the largest revenue?

What is the city with the largest revenue?

What product line had the largest VAT?

Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales

Which branch sold more products than average product sold?

What is the most common product line by gender?

What is the average rating of each product line?

### C. Customer-related questions
How many unique customer types does the data have?

How many unique payment methods does the data have?

What is the most common customer type?

Which customer type buys the most?

What is the gender of most of the customers?

What is the gender distribution per branch?

Which time of the day do customers give most ratings?

Which time of the day do customers give most ratings per branch?

Which day fo the week has the best avg ratings?

Which day of the week has the best average ratings per branch?

### D. Sales-related questions
Number of sales made in each time of the day per weekday

Which of the customer types brings the most revenue?

Which city has the largest tax percent/ VAT (Value Added Tax)?

Which customer type pays the most in VAT?


## Relevant Links
* Challenge Link : Walmart Recruitment - [Store Sales Forecasting](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/overview)

* Dataset Link : [Walmart Sales Dataset](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/data) 

## Contributing
Contributions are always welcome !!

If you would like to contribute to the project, please fork the repository and make a pull request.

Support
If you have any doubts, queries or, suggestions then, please connect with me on LinkedIn.
