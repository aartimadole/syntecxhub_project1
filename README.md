🧹 Automated Data Cleaning & Validation Pipeline using Python & Pandas

A production-style data cleaning and validation pipeline built to simulate real-world data preprocessing workflows used in analytics and consulting environments. 

📌 Project Overview

This project implements an automated data cleaning and validation pipeline to prepare raw datasets for analysis.
It standardizes column names, handles missing values, corrects data types, removes duplicates, detects outliers, and generates a structured cleaning log for transparency.

The objective is to simulate real-world data preprocessing workflows used in analytics and consulting environments.

🚀 Key Features

Standardized column names (lowercase + underscores)

Missing value detection and imputation (median for numeric, mode for categorical)

Date parsing and dtype correction

Duplicate removal

Outlier detection using IQR method

Business validation checks (e.g., negative sales detection)

Before vs After data quality summary

Automated cleaning log generation

Export of cleaned dataset

📊 Dataset

Sample Superstore Dataset
Retail sales dataset containing order details, customer information, sales, profit, and regional data.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook

📂 Project Structure
[syntecxhub_project1/Data_cleaning_utility
](https://github.com/aartimadole/syntecxhub_project1/tree/8881fcdb95daede79e95c71fdd6775341ce34e2a/syntecxhub_project1/Data_cleaning_utility)│
├── data/

│   ├──https://github.com/aartimadole/syntecxhub_project1/blob/66f54750a90b45d5c6db47b535c0c7517424a38e/syntecxhub_project1/Data_cleaning_utility/Sample%20-%20Superstore.csv

│   └── https://github.com/aartimadole/syntecxhub_project1/blob/f73636881cf4f1d8051f01979eb02287983ddcb5/syntecxhub_project1/Data_cleaning_utility/cleaned_dataset.csv

│
├── nothttps://github.com/aartimadole/syntecxhub_project1/blob/beb2e2f0dca73f59fe99d45854f958892ebbdef8/syntecxhub_project1/Data_cleaning_utility/%F0%9F%A7%B9%20Data%20Cleaning%20Utility.ipynbebooks/
│   └── 

│
├── https://github.com/aartimadole/syntecxhub_project1/blob/606deb428595b64487fc75cebad8948189f44b71/syntecxhub_project1/Data_cleaning_utility/cleaning_log.txt
└── README.md

📈 Cleaning Process Summary
1️⃣ Data Standardization

Removed extra spaces

Converted column names to lowercase

Replaced spaces with underscores

2️⃣ Missing Value Handling

Numeric columns → filled using median

Categorical columns → filled using mode

3️⃣ Data Type Validation

Converted date columns to datetime

Ensured numeric columns are properly formatted

4️⃣ Duplicate Removal

Removed duplicate records to improve data integrity

5️⃣ Outlier Detection

Used Interquartile Range (IQR) method to detect extreme sales values

6️⃣ Business Validation

Checked for invalid negative sales values

📁 Output Files

cleaned_dataset.csv

cleaning_log.txt

Summary console report (Before vs After cleaning)

💼 Skills Demonstrated

Data Cleaning & Preprocessing

Data Quality Management

Exploratory Data Analysis (EDA)

Outlier Detection

Data Validation

Automation & Logging

Structured Project Documentation

🎯 Business Value

This pipeline ensures:

Improved data reliability

Reduced manual preprocessing effort

Transparent and reproducible cleaning workflow

Audit-ready documentation

👩‍💻 Author

Aarti Sachin Madole
Aspiring Data Analyst | Python | Pandas | Data Cleaning | EDA

