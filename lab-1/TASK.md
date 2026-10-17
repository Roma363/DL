# Overview

In this lab, you will build and train a simple feedforward neural network (multilayer perceptron, MLP) using only NumPy. You will implement the forward pass, derive and code the backpropagation algorithm, and explore how different activation functions affect training. Finally, you will visualize the decision boundaries your models learn.

## Tasks

- Plot and explore the dataset.
- Build a feedforward neural network with one or more hidden layers.
- Implement forward propagation and binary cross-entropy loss.
- Derive and implement backpropagation for weight updates.
- Run activation function experiments:
  - Sigmoid
  - Tanh
  - ReLU
- Implement and test your own custom activation function.
- Compare effects on convergence and accuracy.

## Allowed Tools

- Python
- NumPy
- Matplotlib (for visualization)

> Deep learning frameworks like PyTorch and TensorFlow, as well as scikit-learn models, are not allowed.

## Timeline

- **Start:** Sep 7, 2025
- **Close:** Dec 31, 2025

## Evaluation

Submissions are evaluated by **ROC AUC** between predicted probabilities and observed target labels.

## Submission File

For each `id` in the test set, predict the probability of the target variable `smoking`.

Required CSV format:

```csv
id,smoking
159256,0.5
159257,0.5
159258,0.5
```
