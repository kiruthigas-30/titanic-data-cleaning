# Titanic Dataset Cleaning and Preprocessing

## Project Overview
This project focuses on cleaning and preprocessing the Titanic passenger dataset as part of a Data Science internship task at Swunex.

## Objective
- Identify and handle missing values.
- Check duplicate records.
- Convert columns to appropriate data types.
- Validate and save the cleaned dataset.

## Tools Used
- Python
- Pandas
- NumPy
- Google Colab

## Dataset
Source: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

The original dataset contains 891 rows and 12 columns.

## Data Cleaning Steps
1. Checked missing values in all columns.
2. Filled missing Age values with the median.
3. Filled missing Embarked values with the most frequent category.
4. Removed the Cabin column because it contained many missing values.
5. Checked for duplicate rows.
6. Converted Pclass, Sex, and Embarked into categorical data types.
7. Validated and exported the cleaned dataset as a CSV file.

## Assumptions
- Median age is used to fill missing Age values.
- The most frequent Embarked value is used to fill missing entries.
- Cabin is excluded from the main cleaned dataset due to extensive missing data.
- Duplicate rows are checked before deciding whether removal is necessary.

## Results
- Original dataset: 891 rows and 12 columns.
- Cleaned dataset: 891 rows and 11 columns.
- Missing values after cleaning: 0.
- Duplicate rows detected: 0.

## Files
- `titanic_data_cleaning.ipynb` — Notebook containing the cleaning process.
- `titanic_cleaned.csv` — Cleaned dataset.

## Conclusion
The dataset was cleaned, validated, and saved for further data analysis.
