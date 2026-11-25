# Overview

**Kaggle task:** [Lab 2 - Feedforward Neural Network](https://www.kaggle.com/competitions/lab-2-feedforward-neural-network/overview)

In this lab, you will build and train a feedforward neural network to
approximate the function

$$
f(x) = x^2.
$$

You will experiment with different network architectures, activation
functions, and optimizers, then visualize the learned function and compare
predictions with the ground truth. The test inputs extend beyond the range of
the training inputs, so the final model must also be evaluated for its ability
to extrapolate.

## Tasks

- Load and explore the training and test datasets.
- Plot the training samples and the ground-truth function.
- Build and train a feedforward neural network using PyTorch.
- Experiment with the number of hidden layers and neurons.
- Compare activation functions and optimizers.
- Record and visualize the training performance over different numbers of
  epochs.
- Evaluate the model with regression metrics such as MSE, MAE, or RMSE.
- Plot the model predictions alongside the ground truth, including over the
  test input range.
- Extend the experiment to approximate a more complex function, for example
  $f(x) = x^3 + 2x$.
- Generate predictions for the test data and save them in the required
  submission format.

## Allowed Tools

- Python
- PyTorch
- NumPy
- Matplotlib (for visualization)

## Evaluation

Evaluate the model using regression metrics such as **Mean Squared Error
(MSE)**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.
Use plots to compare the learned function with the ground truth and discuss the
model's performance on test inputs outside the training range.

## Submission File

For each `id` in the test set, predict the corresponding value of `y` and save
it in the `y_pred` column.

Required CSV format:

```csv
id,y_pred
0,0.0
1,0.0
2,0.0
```
