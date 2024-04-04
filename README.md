# Home Sales Analysis with PySpark

## Overview

This project focuses on analyzing home sales data using PySpark, particularly emphasizing SparkSQL to derive key metrics from the dataset. The primary objectives include determining average prices for homes based on various criteria such as the number of bedrooms, bathrooms, floors, square footage, and year built. Additionally, the project explores caching and uncaching temporary tables to understand their impact on query performance.

## Purpose

The purpose of this project is to demonstrate proficiency in utilizing PySpark and SparkSQL for data analysis tasks. By examining a home sales dataset, we aim to extract valuable insights that could aid in decision-making processes for real estate stakeholders. Through the application of Spark's distributed computing capabilities, we can efficiently process large volumes of data and derive meaningful conclusions.

## Important Findings

- Average prices for four-bedroom houses sold annually indicate slight fluctuations over the years, with the highest average observed in 2021.
- The average price of homes built in different years varies, with certain years showing higher average prices compared to others.
- Filtering homes based on specific criteria such as bedrooms, bathrooms, floors, and square footage allows for more targeted analysis of average prices.
- Caching temporary tables significantly improves query performance, especially for repetitive queries on the same dataset.
- Partitioning data based on the "date_built" field and utilizing parquet formatted data can further enhance query efficiency.

## Summary

This project demonstrates the use of PySpark and SparkSQL to analyze home sales data, deriving insights into average prices based on various property attributes. Through a series of SparkSQL queries, we explore different dimensions of the dataset and evaluate the impact of caching and partitioning on query performance. The findings provide valuable information for understanding market trends and making informed decisions in the real estate domain.

## Screenshots

Placeholder for screenshots

## Technical Details

To run the code provided in this project, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have the necessary dependencies installed, including Spark and Java.
3. Open the `Home_Sales.ipynb` notebook in a compatible environment (e.g., Jupyter Notebook).
4. Execute the code cells sequentially to load the dataset, perform analysis, and observe results.
5. Make sure to adjust any file paths or configurations as needed based on your environment.

## References

- PySpark Documentation
- SparkSQL Documentation
- GitHub Repository for Home_Sales project
