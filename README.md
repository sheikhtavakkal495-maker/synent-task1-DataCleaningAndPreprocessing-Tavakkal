# synent-task1-datacleaning-yourname

## Problem Statement

The Titanic dataset in its raw form has several issues like missing values, duplicate rows, and inconsistent column names that make it unsuitable for direct analysis. The goal here was to clean the data and make it ready for any further work.

## Dataset Details

- Dataset: Titanic Dataset
- Source: Kaggle
- It contains passenger details like age, gender, ticket class, fare, and whether they survived.
- Format: CSV

## Approach

I started by loading the dataset and checking which columns had missing values. The Age column was filled with the median value and Embarked was filled with the most frequent value. The Cabin column had too many missing values so it was dropped entirely. After that I checked for duplicate rows and removed them. Column names were renamed to lowercase with underscores for consistency and data types were corrected wherever needed.

## Results

- All missing values were handled
- Duplicate rows were removed
- Column names are now clean and consistent
- The final dataset is ready for analysis with no null values remaining
