# Multiple Linear Regression From Scratch

This project implements Multiple Linear Regression from scratch using NumPy and Gradient Descent.

## Dataset

California Housing Dataset

Target Variable:
- Median House Value

Features:
- Median Income
- Housing Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Latitude
- Longitude

## Data Preprocessing

- Missing Value Handling
- Feature Scaling (Standardization)
- Numerical Feature Selection

## Features

- Fully Vectorized Implementation
- Cost Function
- Gradient Computation
- Gradient Descent Optimization
- Feature Scaling
- Cost History Tracking
- R² Score Evaluation

## Mathematical Model

Prediction:

ŷ = Xw + b

Cost Function:

J(w,b) = (1/2m) Σ (ŷ - y)²

Gradient:

∇w J = (1/m) Xᵀ(ŷ - y)

∂J/∂b = (1/m) Σ(ŷ - y)

## Results

- R2 Score: 0.6306283922628109
- Successfully predicts housing prices using multiple features.
- Cost decreases consistently during training.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib

## Learning Outcomes

- Multiple Feature Regression
- Vectorization with NumPy
- Feature Scaling
- Matrix Operations
- Gradient Descent Optimization