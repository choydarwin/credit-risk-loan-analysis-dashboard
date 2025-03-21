# Credit Risk and Loan Analysis Dashboard

This project is a comprehensive analysis of credit risk and loan approval trends, culminating in an interactive Power BI dashboard. It includes data loading, cleaning, exploratory data analysis (EDA), and visualization, all documented in Jupyter notebooks.

## Project Overview

This project aims to provide actionable insights into loan approval rates, credit risk factors, and loan characteristics. It is designed for financial analysts and decision-makers to understand the key drivers of loan approvals and identify potential risk areas.

**Note: This project is currently in development and may be subject to changes.**

## Data Processing

The data processing pipeline is documented in the `notebooks` directory.

1.  **Data Loading and Cleaning (`data_loading_and_cleaning.ipynb`)**:
    * Loads raw data from `data/raw_data`.
    * Performs data cleaning tasks, including handling missing values, data type conversions, and removing duplicates.
    * Saves intermediate cleaned data to `data/cleaned_data`.

2.  **Exploratory Data Analysis (`eda.ipynb`)**:
    * Performs exploratory data analysis (EDA) to understand the data distribution, relationships, and potential issues.
    * Generates descriptive statistics and visualizations.

3.  **Loan Data Analysis and Visualizations (`loan_data_analysis_visualizations.ipynb`)**:
    * Performs feature engineering to create relevant features for analysis.
    * Generates visualizations to understand loan approval rates, credit risk factors, and loan characteristics.
    * Saves the final processed data to `data/processed_data/processed_data.csv`.

## Power BI Dashboard

The `power_bi` directory contains the Power BI dashboard (`creditriskloananalysis_dashboard.pbix`). The dashboard is built using the processed data from `data/processed_data/processed_data.csv`.

**Key Visualizations in the Dashboard:**

* Loan approval rates by income category.
* Percentage of approved and denied loans.
* Credit risk and applicant profile analysis (age, credit history, default rates).
* Loan characteristics and intent analysis (loan amount, interest rate, loan intent).

## Author

Darwin Choy

## Dependencies

* Python (with pandas, numpy, matplotlib, seaborn, etc.)
* Power BI Desktop

## Notes

* **Project in Development:** This project is currently in development and may be subject to changes.
