# Data Parsing, Cleansing and Integration Project

## Overview
This project was completed as part of COSC2820 Advanced Programming for Data Science. The project focuses on parsing XML data, identifying and fixing data quality issues, and integrating two datasets into one final schema using Python.

## Objectives
- Parse XML review data into a pandas DataFrame
- Identify and fix data quality issues
- Maintain an error log for auditability
- Resolve schema conflicts between XML and CSV datasets
- Integrate both datasets into one structured dataset

## Tools Used
- Python
- Pandas
- NumPy
- xml.etree.ElementTree
- Jupyter Notebook

## Files
- `S4135999_task1_2.ipynb` – parsing, auditing, and cleansing
- `S4135999_task3.ipynb` – schema conflict resolution and data integration
- `S4135999_dataset1_solution.csv` – cleaned dataset
- `S4135999_errorlist.csv` – audit trail of corrections
- `S4135999_dataset_integrated.csv` – final integrated dataset

## Key Work Completed
- Parsed 6,435 XML records into a source-schema DataFrame
- Cleaned invalid ratings, invalid costs, and inconsistent labels
- Built an error log to document all fixes
- Resolved schema conflicts between dataset1 and dataset2
- Removed exact duplicate records after integration
- Produced a final integrated dataset with 13,782 rows and 11 columns

## Data Quality Issues Addressed
- Invalid numeric values
- Non-integer positive review counts
- Incorrect categorical labels
- Inconsistent department naming
- Duplicate rows after integration

## Screenshots

### Task 1 – Parsing XML data
![Task 1 Parsing](images/task1-parsing.png)

### Task 2 – Data cleaning and validation
![Task 2 Cleaning](images/task2-cleaning.png)

### Task 3 – Final integrated dataset
![Task 3 Integration](images/task3-integration.png)

## What I Learned
This project improved my skills in XML parsing, data cleaning, schema mapping, audit logging, and data integration using Python and pandas.
