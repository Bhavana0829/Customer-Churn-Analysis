# Customer-Churn-Analysis
Customer Churn Data Quality and Exploratory Analysis using Python

# Customer Churn Analysis Using Python

## Project Overview
This project focuses on analyzing customer churn data to identify customer behavior, data-quality issues, and patterns that may contribute to customer loss.

The objective is to prepare a clean, analysis-ready dataset and perform Exploratory Data Analysis (EDA) to understand customer churn.

## Project Objectives
- Analyze customer information.
- Identify missing values and duplicate records.
- Detect potential outliers.
- Clean and prepare the dataset.
- Calculate summary statistics.
- Visualize customer churn patterns.

## Dataset Description
The dataset contains 15 customer records and 11 columns.

Important attributes include:
- CustomerID
- Gender
- Age
- TenureMonths
- SubscriptionType
- MonthlyCharges
- TotalCharges
- ContractType
- SupportTickets
- PaymentMethod
- Churn

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

## Data Cleaning Process
1. Loaded the customer churn dataset using Pandas.
2. Checked column names and data types.
3. Identified missing values.
4. Checked duplicate records and customer IDs.
5. Removed exact duplicate rows.
6. Identified potential outliers using the IQR method.
7. Prepared the cleaned dataset.

## Exploratory Data Analysis
Performed:
- Customer churn distribution analysis.
- Monthly charges distribution analysis.
- Summary statistical analysis.
- Customer data profiling.

## Project Files
- `customer_churn_sample.csv` – Original dataset.
- `cleaned_customer_churn.csv` – Cleaned dataset.
- `customer_churn_analysis.ipynb` – Python analysis notebook.
- `data_quality_report.txt` – Data-quality summary.
- `churn_distribution.png` – Churn visualization.
- `monthly_charges.png` – Monthly charges visualization.

## Key Findings
- Total customer records: 15.
- Total dataset columns: 11.
- Customers who churned: 7.
- Customers retained: 8.
- No missing values were identified in the initial profiling.

## Conclusion
The project demonstrates the process of data profiling, cleaning, and exploratory analysis using Python. The cleaned dataset can be used for further customer segmentation, churn analysis, and business KPI dashboard development.

## Author
Mekala Bhavana

B.Tech – Computer Science and Engineering

