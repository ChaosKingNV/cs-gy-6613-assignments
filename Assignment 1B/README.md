# CS-GY-6613 Assignment 1B
## Submission by: Naman Vashishta (NV2375 N11740506)

This repository contains the code and documentation for **Assignment 1B** of CS-GY-6613. In this assignment, you will implement regularization methods to train linear regression and logistic regression models using PyTorch libraries, without using derived or other external libraries.

## Assignment Tasks

### Linear Regression
#### Task 1: Stochastic Gradient Descent (SGD)
- Implement the baseline Stochastic Gradient Descent (SGD) algorithm for regularized linear regression from scratch using PyTorch’s `torch.xyz` namespace.
- Clearly show the equations related to gradient calculations and weight updates.
- Specify the hyperparameters used and plot the loss vs. epoch to demonstrate the algorithm's convergence. The final hypothesis should also be plotted.

#### Task 2: Momentum
- Implement the momentum algorithm as an alternative to SGD.
- Study the convergence speed by comparing both algorithms.
- Clearly state the hyperparameters used and present a loss vs. epoch plot demonstrating the convergence of both algorithms. You can include both plots in the same figure.

### Logistic Regression
#### Task 1: Data Preprocessing
- Preprocess the dataset for logistic regression, which involves:
  - Dropping unused columns.
  - Handling noisy or missing data.
- Use Pandas for this task and convert the data into PyTorch tensors for later processing.

#### Task 2: Logistic Regression Model
- Implement the logistic regression model for predicting the Click Through Rate (CTR) based on a dataset.
- Use Stochastic Gradient Descent (SGD) for optimization.
- Clearly show the gradient equations and explain every stage of the logistic regression model.
- Highlight any enhancements made to improve the performance of the model.
- Plot the final precision vs. recall curve and explain the tradeoff between the two and the shape of the curve.

## Directory Structure

- `Assignment1B/`: Contains all code and notebooks for Assignment 1B.
- `README.md`: This file, providing an overview of the assignment.

## Screenshots
- Screenshots of the results from your implementation, including any plots of loss vs. epoch, final hypothesis, and precision vs. recall curve.

## Contact
For any questions or clarifications, feel free to contact me at `NV2375@nyu.edu`.

