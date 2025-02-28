Name: Boidapu Sravani

Company: CODETECH IT solutions

Id: CT6WTCS

Domain: Data Science

Duration: February 25th to April 10th, 2025

Mentor: N.Santhosh


## Overview of the project

### Project : Data Pipeline for ETL Process

## Objective:
The project aims to automate the ETL (Extract, Transform, Load) process using Pandas and Scikit-learn, ensuring efficient data preprocessing and transformation for further analysis or machine learning tasks.

## Key Steps in the Pipeline:
-Data Extraction:
A sample dataset is created in the script, which simulates raw data.
The dataset includes numerical features (Age, Salary) and categorical features (City), along with a target column (Purchased).

-Data Preprocessing:
Handling Missing Values: Uses SimpleImputer to fill missing values in numerical columns with the mean.
Scaling Numerical Data: Standardizes numerical values using StandardScaler.
Encoding Categorical Data: Converts categorical values into numerical representations using OneHotEncoder.

-Data Transformation
Uses ColumnTransformer to apply different transformations to numerical and categorical columns efficiently.

-Data Loading:
The transformed dataset is stored in a DataFrame.
Finally, it is saved to a CSV file (processed_data.csv) for further use.

## Deliverable:
A Python script that automates the entire ETL process.
The transformed data is printed and stored in a CSV file.
This pipeline ensures that raw data is cleaned, standardized, and ready for further data science or machine learning applications.
