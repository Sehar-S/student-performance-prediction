# Student-performance-prediction
# Student Performance Prediction Using Machine Learning

## Overview

This project predicts students' final grades (G3) using machine learning techniques and the UCI Student Performance Dataset.

The goal of this project is to identify important factors affecting academic performance and build a predictive model capable of estimating final student grades.

## Dataset

* Source: UCI Machine Learning Repository
* Records: 395 students
* Features: 33 attributes
* Target Variable: G3 (Final Grade)

## Research Question

Which factors have the strongest impact on students' final academic performance, and can machine learning accurately predict final grades?

## Hypothesis

Students with better previous grades and fewer failures are likely to achieve higher final grades.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Jupyter Notebook

## Methodology

1. Data Exploration
2. Feature Selection
3. Train-Test Split
4. Linear Regression Model Training
5. Model Evaluation
6. Result Interpretation

## Selected Features

* studytime
* failures
* absences
* Medu
* Fedu
* G1
* G2

## Results

* MAE: 1.34
* MSE: 4.50
* RMSE: 2.12
* R² Score: 0.78

## Key Findings

* G2 (second-period grade) was the strongest predictor of final performance.
* Previous failures negatively affected student grades.
* Previous academic performance strongly influenced final outcomes.

## Conclusion

The Linear Regression model successfully predicted student performance and explained approximately 78% of the variation in final grades. The project demonstrates the effectiveness of machine learning techniques in educational data analysis.

## Future Improvements

* Random Forest Regression
* XGBoost
* Feature Engineering
* Hyperparameter Tuning
* Interactive Dashboard Development
