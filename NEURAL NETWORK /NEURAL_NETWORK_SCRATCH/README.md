# Neural Network from Scratch for MNIST

A fully connected neural network implemented **from scratch using only NumPy** for handwritten digit classification on the MNIST dataset.

This project was built to understand the mathematics and implementation behind neural networks without relying on deep learning frameworks such as TensorFlow or PyTorch. Every major component, including forward propagation, backpropagation, gradient descent, and weight updates, is implemented manually.


## Project Objective

The goal of this project is to understand how neural networks actually learn by implementing every step manually rather than using high-level APIs.

Instead of calling pre-built layers or optimizers, this project computes:

- Forward Propagation
- ReLU Activation
- Softmax Activation
- Cross-Entropy Loss
- Backpropagation
- Gradient Descent
- Weight & Bias Updates

using only NumPy.


## Network Architecture

```
Input Layer (784)
        │
        ▼
Hidden Layer 1 (128)
        │
      ReLU
        │
        ▼
Hidden Layer 2 (64)
        │
      ReLU
        │
        ▼
Output Layer (10)
        │
     Softmax
        │
        ▼
Prediction
```

## Technologies Used

- Python
- NumPy
- TensorFlow (only for loading the MNIST dataset)
- Matplotlib

No TensorFlow or PyTorch layers, optimizers, or automatic differentiation were used.


## Features Implemented

- He Weight Initialization
- Manual One-Hot Encoding
- Forward Propagation
- ReLU Activation
- Numerically Stable Softmax
- Cross-Entropy Loss
- Manual Backpropagation
- Gradient Descent Optimization
- Prediction Function
- Accuracy Calculation


## Mathematical Concepts Covered

This project implements the mathematics behind neural networks, including:

- Matrix Multiplication
- Chain Rule
- Partial Derivatives
- Gradient Descent
- Cross-Entropy Loss
- ReLU Derivative
- Softmax
- Weight and Bias Updates

All gradients are computed manually without any automatic differentiation library.


## Training Pipeline

```
Load Dataset
      │
      ▼
Normalize Images
      │
      ▼
One-Hot Encode Labels
      │
      ▼
Initialize Weights
      │
      ▼
Forward Propagation
      │
      ▼
Compute Loss
      │
      ▼
Backpropagation
      │
      ▼
Gradient Descent
      │
      ▼
Update Parameters
      │
      ▼
Repeat for Multiple Epochs
      │
      ▼
Predict Test Labels
      │
      ▼
Calculate Accuracy
```


## Learning Highlights

Building this project required understanding both the mathematical theory and the implementation details of neural networks.

Some important implementation decisions included:

- Implementing one-hot encoding manually to match the cross-entropy loss formulation.
- Deriving and implementing forward and backward propagation step by step.
- Verifying gradient calculations and debugging parameter updates.
- Choosing He initialization for improved training with ReLU activations.
- Experimenting with learning rates to achieve stable convergence and better accuracy.
- Understanding why intermediate values (cache) are stored during forward propagation and how they are reused during backpropagation.

Rather than treating the network as a black box, this project focuses on understanding how every parameter is updated during training.


## Results

- Dataset: MNIST Handwritten Digits
- Input Size: 784
- Hidden Layers: 128 → 64
- Output Classes: 10
- Test Accuracy: **~90%**


## Project Structure

```
Neural_Network_Scratch.ipynb

├── Load Dataset
├── Data Preprocessing
├── One-Hot Encoding
├── Weight Initialization
├── Activation Functions
├── Forward Propagation
├── Cross Entropy Loss
├── Backpropagation
├── Gradient Descent
├── Prediction
├── Accuracy
└── Training Loop
```


## Key Takeaway

The primary objective of this project was not only to classify handwritten digits but also to gain a solid understanding of how neural networks work internally.

Implementing every component manually—from matrix operations to gradient computation—provided valuable insight into the optimization process that powers modern deep learning frameworks.