# Logistic Regression From Scratch

This project implements Logistic Regression from scratch using NumPy and Gradient Descent without relying on machine learning libraries.

## Dataset

Breast Cancer Wisconsin Dataset

Target Variable:
- Diagnosis

Classes:
- 0 → Benign
- 1 → Malignant

## Data Preprocessing

- Removed unnecessary columns
- Label Encoding of target variable
- Feature Scaling (Standardization)
- NumPy Vectorization

## Features

- Sigmoid Activation Function
- Binary Cross Entropy Cost Function
- Vectorized Gradient Computation
- Gradient Descent Optimization
- Probability Prediction
- Binary Classification using Thresholding
- Accuracy Evaluation
- Confusion Matrix Analysis

## Mathematical Model

Linear Combination:

z = Xw + b

Sigmoid Function:

f(z) = 1 / (1 + e^(-z))

Cost Function (Binary Cross Entropy):

J(w,b) = -(1/m) Σ [y log(f) + (1-y) log(1-f)]

Gradients:

∇w J = (1/m) Xᵀ(f - y)

∂J/∂b = (1/m) Σ(f - y)

Gradient Descent Updates:

w = w - α∇wJ

b = b - α(∂J/∂b)

## Results

Accuracy: 98.42%

Confusion Matrix:

[[355, 2],
 [  7, 205]]

Precision: 99.03%

Recall: 96.70%

F1 Score: 97.85%

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn (for evaluation metrics only)

## Learning Outcomes

- Logistic Regression Fundamentals
- Binary Classification
- Sigmoid Activation Function
- Vectorized Gradient Descent
- Feature Scaling
- Model Evaluation using Accuracy, Precision, Recall, F1 Score and Confusion Matrix