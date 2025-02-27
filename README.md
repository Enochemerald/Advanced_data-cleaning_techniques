# Advanced Data Cleaning Techniques

## Introduction
This repository contains an SQL script that demonstrates advanced data cleaning techniques using a dataset on layoffs. The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/swaptr/layoffs-2022) and is analyzed within a MySQL environment. The script performs various data transformation and cleaning steps to ensure data integrity and accuracy.

## Objectives
The main objectives of this data cleaning techniques are:
- To identify and remove duplicate records.
- To standardize missing or inconsistent data.
- To enhance data quality for better analysis and decision-making.

## Approach
The script follows a structured approach:
1. **Database Setup**: A new database `world_layoffs` was created and the dataset is loaded.
2. **Staging Table Creation**: A staging table `layoffs_staging` was created to hold raw data before cleaning operations.
3. **Duplicate Handling**: The script identified duplicate records using `ROW_NUMBER()` and removes them to ensure data uniqueness.
4. **Data Standardization**: Placeholder steps for formatting and handling missing data are included for consistency.
5. **Final Data Processing**: Cleaned data is prepared for further analysis.


