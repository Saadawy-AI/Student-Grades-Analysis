# 📘 Student Grades Analysis

## Overview
A data analysis project to evaluate and predict student performance based on six subjects. Includes grades, final scores, letter grades (A–F), and allowed hours for next semester.

## Dataset Columns
- Student_ID (6-digit)
- Name
- Math, Physics, Chemistry, English, Biology, History
- Final Grade (average of subjects)
- Grade Letter (A–F)
- Registered Hours (fixed at 18)
- Allowed Hours Next Semester (15 / 18 / 21 based on final grade)

## Visualizations
- Histograms & Boxplots (per subject)
- Correlation Heatmap
- Grade Distribution (bar & pie charts)
- Line chart for student comparison
- Pairplot of subject relationships

## Grade Prediction
- Model: Random Forest Classifier
- Inputs: Subject grades
- Output: Letter grade
- Includes: Classification report & Confusion matrix

## Requirements
```bash
pip install pandas matplotlib seaborn scikit-learn
```

## Author
- Your Name - 2025
