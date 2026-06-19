# Student Performance Analysis

## Overview

This project analyzes the Student Performance Dataset from the UCI Machine Learning Repository. The goal is to explore what factors are related to students’ final grades and build models to predict student performance.

## Research Question

What factors are most related to student final grades?

## Dataset

The dataset contains information about Portuguese secondary school students, including:

- Demographics
- Family background
- Study time
- Absences
- Alcohol consumption
- Parent education
- Past failures
- Grades

The main target variable is:

- `G3`: final grade

## Methods

This project includes:

- Data cleaning
- Exploratory data analysis
- Data visualization
- Regression modeling
- Model comparison

The models used include:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression
- Random Forest Regression

## Key Findings

- Previous grades are strongly related to final grades.
- Students with more past failures tend to have lower final grades.
- Study time has a positive relationship with final grade.
- Absences and alcohol consumption may be related to lower performance, but the relationship is not very strong.
- Student performance is influenced by many factors, so it is difficult to predict perfectly.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Files

```text
student_performance.csv
student_performance.ipynb
student_performance.html
README.md
