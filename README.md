# Real Data and Problem Framing

This repository focused on real-world data analysis and problem framing. It involved exploring messy datasets, identifying data quality issues, understanding business context, and defining the right problem before moving toward analysis or machine learning.

## Overview

Real-world datasets rarely arrive clean. They often contain:

- missing or blank values
- inconsistent formats
- invalid or impossible entries
- duplicate rows
- mixed data types
- poorly standardized categories

This project demonstrates how to inspect, clean, and interpret such data using Python, pandas, and visualization tools. The work emphasizes data quality, structured thinking, and business-aware decision-making.

## Repository Structure

```text
Real-Data-and-Problem-Framing/
│
├── Day1/
│   ├── Day1.ipynb
│   └── Day1.md
│
├── Project1a/
│   ├── Data processing.ipynb
│   ├── healthcare_messy_data.csv
│   ├── cleaned.csv
│   ├── DATA_REPORT.md
│   ├── age_distribution.png
│   ├── gender_distribution.png
│   ├── condition_distribution.png
│   ├── cholesterol_distribution.png
│   └── missing_values.png
│
├── Project1b/
│   ├── Data cleaning/
│   │   ├── Data cleaning.ipynb
│   │   ├── clean_financial_transactions.csv
│   │   ├── data_report.md
│   │   └── .DS_Store
│   └── Messy data analysis/
│       ├── exploring the raw dataset.ipynb
│       ├── dirty_financial_transactions.csv
│       ├── data report.md
│       └── .DS_Store
│
└── README.md
```

## Projects Included

### Day 1: Foundations of Data Quality and Problem Framing

This section introduces the core skills required for working with real data:

- dataset exploration
- feature understanding
- missing value detection
- type validation
- duplicate detection
- categorical consistency checks

The work focuses on a Telco Customer Churn dataset and highlights an important lesson: blank strings can look like valid values while actually representing missing data.

Key takeaway:
- empty strings may not be recognized by `isnull()`
- therefore, data type and missing-value issues must be checked carefully before analysis

### Project 1a: Healthcare Dataset Cleaning

This project works with a messy healthcare dataset containing patient information such as age, gender, diagnosis, medication, visit dates, blood pressure, cholesterol, email, and phone numbers.

Main cleaning tasks:

- corrected invalid numeric values
- standardized date formats
- removed extra whitespace
- handled missing values based on column type
- filled categorical values using mode
- filled numeric values using median
- preserved unique identifiers where imputation was not appropriate
- checked duplicates and outliers

Outputs include:

- cleaned dataset
- visualizations of distribution and missingness
- a data-quality report

### Project 1b: Financial Transactions Data Cleaning and Analysis

This project uses a large, intentionally messy financial transactions dataset.

It covers:

- data auditing and exploratory analysis
- detection of inconsistent values and invalid dates
- cleaning of currencies, price fields, and dates
- normalization of payment methods and transaction statuses
- duplicate removal and validation of numeric fields
- product-name standardization and distribution analysis

This project is especially useful for learning how a dirty dataset can distort analysis if not cleaned properly.

## Skills Demonstrated

This repository emphasizes the following data science and analytics practices:

- data profiling
- data cleaning
- missing value strategy
- standardization and normalization
- feature quality assessment
- business-aware problem framing
- reproducible reporting through notebooks and markdown summaries

## Tools and Libraries

The projects primarily use:

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebooks

## Learning Objectives

By working through this repository, a learner should be able to:

1. identify data quality issues in real-world datasets
2. decide when to impute, drop, or retain values
3. standardize inconsistent categories and formats
4. understand why data type checks matter before analysis
5. frame a problem based on noisy, imperfect data
6. produce clear documentation and reporting for data cleaning work

## Notes

This repository is designed as a practical introduction to real-data problem framing. It demonstrates that data work is not only about coding—it is also about interpreting the data, understanding the business context, and making defensible cleaning decisions.


