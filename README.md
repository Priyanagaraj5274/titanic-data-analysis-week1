# Titanic Data Analysis – Week 1

## Overview

This project was completed as part of a Data Science Internship Week 1 task.

The project focuses on:

- Data acquisition
- Data cleaning
- Missing-value handling
- Duplicate detection
- Infinite-value detection
- Exploratory Data Analysis (EDA)
- Data visualization
- Feature engineering
- Correlation analysis
- Insight generation

## Dataset

The project uses the Titanic passenger dataset.

The original dataset contains:

- 891 passenger records
- 12 columns

The target variable is `Survived`, where:

- `0` = Did not survive
- `1` = Survived

## Data Cleaning

The following preprocessing steps were performed:

### Missing Values

- `Cabin`: 687 missing values (77.10%) → column removed
- `Age`: 177 missing values (19.87%) → median imputation
- `Embarked`: 2 missing values (0.22%) → mode imputation

### Other Checks

- Duplicate records found: 0
- Infinite numerical values found: 0

## Feature Engineering

Two additional features were created:

- `FamilySize`
- `AgeGroup`

## Exploratory Data Analysis

The project analyzes:

- Overall survival distribution
- Survival by gender
- Survival by passenger class
- Age distribution
- Fare distribution
- Family-size patterns
- Survival by age group
- Correlations between numerical variables

## Key Findings

- Overall survival rate: **38.38%**
- Female survival rate: **74.20%**
- Male survival rate: **18.89%**
- First-class survival rate: **62.96%**

These results indicate substantial differences in survival outcomes across gender and passenger class.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Project Files

- `Week1_Titanic_Data_Analysis.ipynb` – Complete analysis notebook
- `titanic_cleaned_final.csv` – Final cleaned dataset
- `visualizations/` – Generated charts and visualizations

## Author

**Priya N**
