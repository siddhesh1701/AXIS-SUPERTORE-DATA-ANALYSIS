# AXIS-SUPERTORE-DATA-ANALYSIS
DATA ANALYSIS REPORT
# Data Analysis Project Using Excel

## Overview
This project aims to analyze a dataset containing various elements such as Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, and Profit. We will answer four major questions using this dataset and create a dashboard to visualize the results.

## Dataset Description
The dataset includes the following columns:
- **Ship Mode**: The mode of shipment for the product.
- **Customer ID**: Unique identifier for each customer.
- **Customer Name**: Name of the customer.
- **Segment**: The customer segment (Corporate, Consumer, Home-Office).
- **Country**: The country where the product is sold.
- **City**: The city where the product is sold.
- **State**: The state where the product is sold.
- **Postal Code**: The postal code of the customer's location.
- **Region**: The region where the product is sold.
- **Product ID**: Unique identifier for each product.
- **Category**: The category of the product.
- **Sub-Category**: The sub-category of the product.
- **Product Name**: The name of the product.
- **Sales**: The sales amount for the product.
- **Quantity**: The quantity of the product sold.
- **Discount**: The discount applied to the product.
- **Profit**: The profit made from the product.

Additionally, there is a separate sheet containing the following columns:
- **Product ID**: Unique identifier for each product.
- **Ship Charge**: The shipping charge for the product.

## Key Questions Answered

1. **Which Segment amongst the Corporate, Consumer, and Home-Office ones had the highest average Sales?**
   - **Analysis**: Calculate the average sales for each segment and identify the segment with the highest average sales.

2. **What is the average order Quantity for the customer ‘Clay Rozendal’?**
   - **Analysis**: Filter the data for the customer 'Clay Rozendal' and calculate the average order quantity. Round off the answer to the nearest integer.

3. **Which Category brought in the highest average Profit for the products that had a 'Standard Class' Ship Mode?**
   - **Analysis**: Filter the data for products with 'Standard Class' ship mode and calculate the average profit for each category. Identify the category with the highest average profit.

4. **Which Region has the highest average in Ship Charges?**
   - **Analysis**: Using the separate sheet with shipping charges, merge the data with the main dataset based on Product ID. Calculate the average ship charge for each region and identify the region with the highest average ship charge.

## Steps for Analysis

1. **Load the Data**:
   - Import the dataset and the shipping charges sheet into Excel.

2. **Data Cleaning and Preparation**:
   - Ensure all columns are correctly formatted (e.g., numerical columns are formatted as numbers).
   - Check for any missing or inconsistent data and clean the dataset accordingly.

3. **Calculations**:
   - Use Pivot Tables, Filters, and Formulas in Excel to calculate the required metrics for each question.
   - Create additional columns if necessary (e.g., for average calculations).

4. **Dashboard Creation**:
   - Use Excel’s dashboard features to create a visual representation of the results.
   - Include charts, graphs, and key metrics to summarize the findings for each question.
   - Ensure the dashboard is interactive and user-friendly, allowing for easy exploration of the data.

## Conclusion
This README file outlines the process and methodology for analyzing the dataset to answer the four major questions and create a comprehensive dashboard. The steps provided will guide you through loading the data, preparing it for analysis, performing the necessary calculations, and summarizing the results in an interactive dashboard.
