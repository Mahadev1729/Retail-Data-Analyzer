# Retail-Data-Analyzer

This project performs a detailed analysis of sales data from a CSV file. The script includes operations such as handling missing values, calculating total sales, analyzing performance metrics, and saving results to a new CSV file.

Features

Read Data:

Reads sales data from sales_data.csv using pandas.

Handle Missing Values:

Identifies and fills missing values in numeric columns with their respective column means.

Calculate Total Sales:

Computes a new column Total Sales as the product of Units Sold and Price per Unit.

Aggregate Metrics:

Calculates total sales.

Computes average sales per product.

Identifies the best-selling product.

Date and Time Analysis:

Extracts the month from the Date column and computes monthly sales.

Statistical Metrics:

Calculates mean, median, and standard deviation of total sales.

Save Results:

Exports the updated DataFrame to a new CSV file sales_data_analysis.csv.

Requirements

Ensure the following Python libraries are installed:

pandas

numpy

You can install these using pip: pip install numpy pandas
