DATA CLEANING PROJECT

Overview

This repository contains the data cleaning workflow for dirty sales dataset.
The goal is to transform raw, messy data into a reliable, analysis-ready dataset by handling missing values, inconsistent formats, and outliers.

Objectives

a. Inspect raw data for quality issues.

b. Standardize column names, data types, and formats.

c. Handle missing or duplicate records.

d. Identify and treat outliers or anomalies.

e. Produce a clean dataset ready for analysis or modeling


-- How to Run

Interactive notebooks: Open the .ipynb files in Jupyter or VS Code and run cells step by step.

--Tools & Libraries

Python 3.x

pandas, numpy

matplotlib / seaborn for data visualization

--Key Cleaning Steps

a. Data Profiling: Basic statistics, missing-value checks, duplicates.

b. Standardization: Column naming conventions, date/time formats, converting text to numbers

c. Missing Data Handling: Imputation, deletion, or domain-specific replacements.

d. Outlier Treatment: Z-score, IQR, or domain logic.

e. Validation: Ensuring row/column counts, schema, and summary stats match expectations.


-- Quality Checks

a. Automated tests for column types and null thresholds (pytest or custom checks).

b. Visual inspection plots for distributions before and after cleaning.

[Download raw_data.csv] : (http://localhost:8888/files/Desktop/DATA%20TYPES/DIRTY%20DATA.csv?_xsrf=2%7C6f58050f%7C01fd10678122998204be4576559e7b90%7C1757099092)
