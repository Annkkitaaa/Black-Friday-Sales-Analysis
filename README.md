# Black Friday Market Analysis

## Overview
Black Friday is a renowned shopping holiday occurring the day after Thanksgiving, known for substantial discounts and special deals across various product categories. This project aims to provide valuable insights into the market through a thorough analysis of a dataset containing 537,578 rows and 12 columns. The primary tools for analysis include Pandas, Numpy, and Seaborn.

## Project Structure

### 1. Dataset Walkthrough
   - Explore column names, data types, and identify null values.
   - Address null values in the `Product_Category_2` and `Product_Category_3` columns by removing the entire columns.

### 2. Analyzing Columns
   - Utilize `unique()` and `nunique()` functions to determine the number of unique values in each column.
   - Extract insights, such as the total number of customers (`User_ID`) and products (`Product_ID`).

### 3. Analyzing Gender
   - Focus on the `Gender` column.
   - Observe that the dataset contains more male data than female data.
   - Use groupby functions and visualize with pie charts and bar plots to understand purchasing patterns.

### 4. Analyzing Age & Marital Status
   - Analyze the `Age` and `Marital Status` columns.
   - Use groupby functions to identify age groups with the highest number of orders and purchasing amounts.
   - Visualize findings with pie charts and bar plots.

### 5. Multi-Column Analysis
   - Extend analysis to multiple columns using Seaborn.
   - Utilize Seaborn library to visualize relationships between `Age` and `Gender`, adding legends for better interpretation.

### 6. Combining Gender & Marital Status
   - Combine the `Gender` and `Marital Status` columns.
   - Employ Seaborn for data visualizations, particularly using countplot, to reveal meaningful insights.

## Conclusion
This project aims to offer a comprehensive analysis of the Black Friday dataset, providing actionable insights for companies in understanding customer behavior and market trends. Each section contributes to a deeper understanding of the dataset, visualizing key patterns and relationships. The implementation of Pandas, Numpy, and Seaborn ensures a robust analytical approach.
