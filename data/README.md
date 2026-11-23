
# Data Documentation

## Dataset Name
Student Performance Dataset

## Data Source
UCI Machine Learning Repository:
https://archive.ics.uci.edu/dataset/320/student+performance

## Original Data Files
The original dataset contains two CSV files:

- student-mat.csv: Mathematics student records (395 rows).
- student-por.csv: Portuguese student records (649 rows).

Both files contain 33 columns describing student characteristics,
study habits, absences, and academic grades.

## Data Format
The original CSV files use a semicolon (;) as a separator.

## Data Preparation
The two datasets were loaded separately using Pandas.
A Subject column was added to identify each subject.
The datasets were then concatenated into one combined dataset.

An additional column, Average_Grade, was calculated
as the mean of G1, G2, and G3.

## Final Dataset
File: student_performance_cleaned.csv

Shape: 1044 rows and 35 columns.

The final dataset is stored in this folder.

## Data Quality
- No missing values were found.
- No duplicate rows were found.
- No negative absence values were found.

## Important Note
The two subject datasets were concatenated, not merged using
individual student identifiers. Therefore, the combined records
should not be interpreted as matched individual students.
