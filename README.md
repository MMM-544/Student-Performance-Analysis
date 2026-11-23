
# Student Performance Analysis Using Python

## 1. Project Overview

This project analyzes student performance data in Mathematics and Portuguese.
It explores academic results and examines factors related to students' achievement.

## 2. Project Objectives

- Analyze students' final grades in Mathematics and Portuguese.
- Compare academic performance across different subjects.
- Explore the relationship between study time and final grades.
- Examine the relationship between student absences and final grades.
- Apply data cleaning, transformation, aggregation, and visualization techniques.

## 3. Dataset Source

UCI Machine Learning Repository – Student Performance Dataset.

https://archive.ics.uci.edu/dataset/320/student+performance

The dataset includes two original files:
- Mathematics: 395 records.
- Portuguese: 649 records.

## 4. Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 5. Data Preparation

The following steps were performed:

- Loaded both subject datasets.
- Inspected dataset dimensions, columns, and data types.
- Checked missing values and duplicate records.
- Checked grade ranges and negative absence values.
- Added a Subject column.
- Combined the datasets using concatenation.
- Created an Average_Grade column.
- Aggregated final grades by subject and study time.

## 6. Data Analysis and Main Findings

- Mathematics average final grade: 10.42.
- Portuguese average final grade: 11.91.
- Average final grade generally increased with study time up to the 5–10 hours category.
- The scatter plot shows variation in final grades across different absence levels.

## 7. Visualizations

Three visualizations were created:

1. Average Final Grade by Subject.
2. Study Time and Average Final Grade.
3. Relationship Between Student Absences and Final Grades.

The figures are available in the outputs/figures folder.

## 8. Data Quality

- No missing values were found.
- No duplicate rows were found.
- No negative absence values were found.

## 9. Limitations

- The two subject datasets have different numbers of records.
- The datasets were concatenated, not matched using individual student identifiers.
- The analysis describes associations and does not establish causation.
- Other factors may influence academic performance.

## 10. Reproducibility

The analysis was developed in Google Colab.

To reproduce the analysis:
1. Open the notebook in Google Colab.
2. Run all cells from top to bottom.
3. The notebook downloads and extracts the original dataset.
4. The notebook performs data preparation, analysis, and visualization.

Required libraries: pandas, numpy, matplotlib, and seaborn.

## 11. Team Contributions

Team member names and individual contributions should be added here.

## 12. Project Structure

- data/: Cleaned dataset and data documentation.
- notebooks/: Project analysis notebook.
- outputs/figures/: Generated visualizations.
- README.md: Project documentation.
