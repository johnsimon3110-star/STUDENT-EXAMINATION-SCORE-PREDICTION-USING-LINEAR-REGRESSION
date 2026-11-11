# Student Performance Prediction Using Linear Regression

## 1. Project Overview

This project investigates the application of Linear Regression to predict students' examination scores using academic, behavioural, and personal factors.

The project compares two Linear Regression models to examine how the number of independent variables affects predictive performance.

## 2. Project Objectives

- Apply Linear Regression to a real-world student performance dataset.
- Investigate the relationship between study habits and examination scores.
- Develop and evaluate two regression models.
- Compare simple and multiple Linear Regression.
- Evaluate model performance using standard regression metrics.

## 3. Dataset Description

The project uses a student performance dataset containing 6,607 records.

- Total observations: 6,607
- Independent variables: 19
- Target variable: Exam Score
- Training data: 80%
- Testing data: 20%

## 4. Methodology

The project follows these stages:

1. Dataset loading and exploration.
2. Data cleaning and preprocessing.
3. Numerical and categorical feature preparation.
4. Training and testing data splitting.
5. Linear Regression model development.
6. Model training and prediction.
7. Model evaluation.
8. Comparative analysis and visualization.

## 5. Models Developed

### Model A: Linear Regression with Two Predictors

This model uses two independent variables:

- Attendance
- Hours Studied

**Regression equation:**

\[
\hat{Y}=b_0+b_1X_1+b_2X_2
\]

### Model B: Multiple Linear Regression

This model uses all 19 independent variables to predict examination scores.

**Regression equation:**

\[
\hat{Y}=b_0+b_1X_1+b_2X_2+\cdots+b_{19}X_{19}
\]

## 6. Evaluation Metrics

Both models are evaluated using:

- R-squared (R²)
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## 7. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- GitHub

## 8. Repository Structure

```text
Linear-Regression-Assignment/
│
├── README.md
├── linear_regression.ipynb
├── requirements.txt
├── data/
├── results/
├── graphs/
├── report.pdf
└── .gitignore
```

## 9. Results and Discussion

The two regression models are compared to investigate whether using all 19 independent variables improves predictive performance compared with using only Attendance and Hours Studied.

The evaluation results, graphs, and discussion are provided in the project notebook and final report.

## 10. Conclusion

This project demonstrates the implementation and evaluation of Linear Regression for student examination score prediction. By comparing two models with different numbers of predictors, the study investigates the importance of feature selection and the contribution of multiple independent variables to predictive performance.

