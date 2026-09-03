# Neural Network From Scratch with NumPy

This project implements a simple neural network from scratch using only NumPy.

The goal of this project is to understand how neural networks actually work internally instead of relying on automatic differentiation frameworks.

The project includes:

- Forward propagation
- Hidden layers
- Tanh activation
- Mean Squared Error (MSE) loss
- Manual backpropagation
- Gradient calculation
- Weight and bias updates using Gradient Descent

---

## Network Architecture

The neural network follows this structure:

```text
Input
  ↓
Linear Layer (W1, b1)
  ↓
h1
  ↓
Tanh Activation
  ↓
act
  ↓
Linear Layer (W2, b2)
  ↓
h2
  ↓
Loss