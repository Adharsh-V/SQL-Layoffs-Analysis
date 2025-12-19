# SQL-Layoffs-Analysis
Data cleaning of a global layoffs dataset using SQL to prepare structured and analysis-ready data.

📌 Project Overview
This project focuses on cleaning a raw global layoffs dataset using SQL.
The objective is to improve data quality and make the dataset ready for future analysis.


#  Dataset
- Global layoffs raw dataset
- Contains company name, industry, location, dates, and layoff numbers
- Raw data had issues such as duplicates, null values, and inconsistent formatting

# Data Cleaning Steps Performed
The following data cleaning operations were performed using SQL:

- Removed duplicate records
- Standardized company and industry names
- Handled NULL and blank values
- Trimmed unwanted spaces
- Converted date columns into proper format
- Cleaned numerical fields
- Created a final cleaned table

# 🛠 Tools Used
- SQL
- MySQL


- # 📂 Project Structure
sql-layoffs-analysis/
├── README.md
├── sql/
│ └── layoffs_data_cleaning.sql
├── data/
│ ├── layoffs_raw.csv
│ └── layoffs_cleaned.csv

