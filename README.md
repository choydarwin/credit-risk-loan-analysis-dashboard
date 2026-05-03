## Credit Risk and Loan Analysis Dashboard 📊  

This project analyzes credit risk and loan approval trends through an end-to-end data processing workflow and an interactive Power BI dashboard. It covers data ingestion, cleaning, transformation, and visualization, with all steps documented in Jupyter notebooks.

### **Project Overview**  
The goal is to provide insights into loan approval rates, credit risk, and loan characteristics, supporting data-driven decision-making for financial analysis. The project focuses on structuring and preparing data for reliable analysis and dynamic visualization.

**Note:** This project is still in progress.

### **Data Processing (Python Workflow)**  
- **Data Ingestion & Cleaning:** 📥 Uses Pandas to load raw data, handle missing values, convert data types, and remove duplicates, ensuring data quality and consistency.  
- **Exploratory Data Analysis (EDA):** 📊 Performs statistical analysis and visualization using Pandas, Matplotlib, and Seaborn to understand distributions, relationships, and data integrity.  
- **Data Transformation & Feature Engineering:** ⚙️ Applies transformations and feature engineering to prepare structured datasets for downstream analysis and visualization.  

The data processing workflow is designed to ensure clean, consistent, and analysis-ready datasets for integration with the visualization layer.

![Demo GIF](https://github.com/choydarwin/credit-risk-loan-analysis-dashboard/blob/main/notebooks/eda.gif)

---

### **Power BI Dashboard**  
The **power_bi** folder contains the interactive dashboard (**creditriskloananalysis_dashboard.pbix**), built on the processed datasets.

![Demo GIF](https://github.com/choydarwin/credit-risk-loan-analysis-dashboard/blob/main/power_bi/credit_risk.gif)

#### **Key Visuals in the Dashboard:**  
- Loan approval rates by income category  
- Approved vs. denied loan percentages  
- Credit risk and applicant profile analysis (age, credit history, default rates)  
- Loan details and intent analysis (loan amount, interest rate, loan purpose)  

The dashboard leverages DAX measures and dynamic filtering to enable interactive analysis and segmentation of credit risk factors.

---

### **Author**
Darwin Choy
