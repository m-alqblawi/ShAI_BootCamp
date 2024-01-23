# Salary Analysis

This repository contains a Jupyter notebook that performs an analysis on a salary dataset. The analysis includes basic data exploration, descriptive statistics, data cleaning, data visualization, grouped analysis, and simple correlation analysis.

## Summary of Insights

1. **Basic Data Exploration**: The dataset contains 148,654 rows and 13 columns. The columns are of different data types: numerical, categorical, etc. There were missing values in some columns which were handled in the data cleaning process.

2. **Descriptive Statistics**: The average salary is approximately 74,768.32, with a median of 71,426.61. The range of salaries is from 618.13 to 567,595.43, with a standard deviation of 50,517.01.

3. **Data Cleaning**: Missing data was handled by dropping columns with more than 50% missing values and filling other missing values with the median for numerical columns and mode for categorical columns.

4. **Basic Data Visualization**: The histogram of salaries showed a certain distribution (e.g., normal, skewed, etc.). The pie chart showed that the largest proportion of employees work in the 'Transit Operator' department.

5. **Grouped Analysis**: The summary statistics showed differences in pay across different job titles. The job title with the highest average salary is 'GENERAL MANAGER-METROPOLITAN TRANSIT AUTHORITY'.

6. **Simple Correlation Analysis**: There is a strong positive correlation between 'TotalPay' and 'TotalPayBenefits'. The scatter plot visualizes this relationship.

## Dataset

The dataset used in this analysis is included in this repository. It contains information about salaries and job titles.

## Requirements

To run the Jupyter notebook, you will need Python and the following libraries: pandas, numpy, matplotlib, seaborn.
