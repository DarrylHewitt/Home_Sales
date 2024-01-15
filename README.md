# Home_Sales

## Introduction
This PySpark project focuses on leveraging SparkSQL to analyze essential metrics related to home sales data. The following tasks were performed to gain insights into the dataset:

## Project Setup
1. **Repository Creation:**
    - Established a new repository named Home_Sales.
    - Cloned the repository to the local machine.

2. **Code Initialization:**
    - Renamed the Home_Sales_starter_code.ipynb file to Home_Sales.ipynb.

3. **GitHub Interaction:**
    - Pushed the changes to the GitHub repository.

## SparkSQL Analysis

4. **Importing Necessary PySpark SQL Functions:**
    - Imported the required PySpark SQL functions for the analysis.

5. **Data Ingestion:**
    - Read the home_sales_revised.csv data into a Spark DataFrame.

6. **Creating Temporary Table:**
    - Created a temporary table named "home_sales."

7. **Answering Key Questions:**
    - Utilized SparkSQL to answer specific questions, such as average prices for different house configurations and view ratings.

8. **Caching Temporary Table:**
    - Cached the "home_sales" temporary table for optimized performance.

9. **Checking Cache Status:**
    - Verified whether the temporary table "home_sales" was successfully cached.

10. **Filtered Query with Cache:**
    - Ran a query on the cached data, filtering out view ratings with an average price greater than or equal to $350,000.

11. **Partitioning Parquet Data:**
    - Partitioned the data by the "date_built" field and saved it in the Parquet format.

12. **Temporary Table for Parquet Data:**
    - Created a temporary table for the formatted parquet home sales data.

13. **Filtered Query with Parquet Data:**
    - Ran a query on the parquet data, filtering out view ratings with an average price greater than or equal to $350,000.

14. **Uncaching Temporary Table:**
    - Uncached the "home_sales" temporary table.

15. **Verification of Uncaching:**
    - Verified that the "home_sales" temporary table was successfully uncached using PySpark.

## Conclusion
The Home_Sales SparkSQL project successfully addressed the specified tasks, providing valuable insights into key metrics related to home sales data. Home_Sales.ipynb captures the entire process, and the code is organized and well-documented for clarity.

**Note:** The Jupyter notebook file, `Home_Sales.ipynb`, has been uploaded to the GitHub repository named Home_Sales.

