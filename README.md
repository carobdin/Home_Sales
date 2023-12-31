# Module 22 Report

## Overview
This project aims to analyze home sales data using SparkSQL within a Jupyter Notebook environment. The key objectives include extracting insights and determining key metrics from the dataset. The analysis involves creating temporary views, partitioning the data, caching and uncaching a temporary table, and verifying the successful uncaching of the table.

## Getting Started
1. Clone the repository:
git clone https://github.com/carobdin/Home_Sales

2. Install the required Python packages:
pip install pyspark

3. Start Jupyter Notebook:
jupyter notebook
Open the Home_Sales.ipynb notebook.

## Notebook Structure
The Jupyter Notebook is structured as follows:

1. Data Loading and Exploration:

Load the home sales dataset.
Explore the dataset to understand its structure and content.

2. SparkSQL Analysis:

Utilize SparkSQL to perform SQL queries on the home sales data.
Create temporary views to facilitate SQL queries.

3. Data Partitioning:

Partition the dataset based on relevant columns.

4. Caching and Uncaching:

Cache the temporary table to improve performance for repeated queries.
Uncache the temporary table when the caching is no longer needed.

5. Key Metrics:

Calculate and display key metrics related to home sales.

6. Verification:

Verify that the table has been successfully uncached.

## Usage
Follow the instructions within the Jupyter Notebook to execute each cell sequentially. The notebook provides detailed comments and explanations for each step of the analysis.

## References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
