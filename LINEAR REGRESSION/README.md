# Linear Regression From Scratch

This project implements Simple Linear Regression from scratch using NumPy and Gradient Descent without using machine learning libraries.

## Dataset

Salary Dataset

Target Variable:
- Salary

Feature:
- Years of Experience

## Features

- Data Loading using Pandas
- Cost Function Implementation
- Gradient Descent Optimization
- Prediction Function
- Cost vs Iterations Visualization
- Regression Line Visualization
- R² Score Evaluation

## Mathematical Model

Prediction:

ŷ = wx + b

Cost Function:

J(w,b) = (1/2m) Σ (ŷ - y)²

Gradient Descent Updates:

w = w - α(dJ/dw)

b = b - α(dJ/db)

## Results

- Successfully learned the relationship between experience and salary.
- Cost decreases over iterations.
- Regression line fits the data.
- R2 Score: 0.9569159787361847

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib

## Learning Outcomes

- Understanding Gradient Descent
- Cost Function Optimization
- Model Evaluation using R² Score
- Building ML algorithms from scratch