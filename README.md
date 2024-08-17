# Retail Order Analysis Using SQL and Python

## Objective:

The primary objective of this project is to perform comprehensive data analysis on a retail orders dataset to derive meaningful insights that can help in understanding sales performance, customer behavior, and product trends. This includes tasks such as calculating discounts, sale prices, and profits, identifying top-performing products, analyzing sales growth, and understanding regional sales trends.

## Idea Behind the Project:

The idea was to streamline the process of extracting, transforming, and loading data to make it suitable for analysis. By doing this, we can derive insights that can help businesses make data-driven decisions. The goal was to build an efficient ETL pipeline and perform SQL queries to uncover key metrics and trends in the retail data.

## Steps Followed during the project

Data Extraction:

Downloaded dataset from Kaggle using Kaggle API.
Extracted the dataset from a zip file.

Data Transformation:
Read the dataset with pandas, handling null values.
Renamed columns to lowercase and replaced spaces with underscores.
Derived new columns for discount, sale price, and profit.
Converted order_date from object data type to datetime.
Dropped unnecessary columns.

Data Loading:
Connected to PostgreSQL database using SQLAlchemy.
Loaded the transformed data into PostgreSQL.

Data Analysis:
Executed SQL queries to analyze data:
Identified top 10 highest revenue-generating products.
Found top 5 highest selling products in each region.
Conducted month-over-month growth comparison for 2022 and 2023 sales.
Determined the month with the highest sales for each category.
Identified sub-category with the highest growth in profit from 2022 to 2023.


