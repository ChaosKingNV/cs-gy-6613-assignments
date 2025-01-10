# CS-GY-6613 Assignment 1A
## Submission by: Naman Vashishta (NV2375 N11740506)

This repository contains the code and documentation for **Assignment 1A** of CS-GY-6613. In this assignment, you will set up the development environment, simulate multivariate normal distributions, and implement basic machine learning techniques like K-Means clustering and PCA using PyTorch libraries.

## Assignment Tasks

### Development Environment Setup
- Set up your development environment following the instructions from the course site.
- Install Docker on your machine and clone the repository. (For Windows users, clone it to the WSL2 filesystem).
- Build and launch the Docker container inside your desired IDE (VSCode is recommended).
- Launch the virtual environment inside the container using `rye sync` and show a screenshot of your terminal with the virtual environment prefix.

### Simulation of Multivariate Normal Distribution
- Generate samples from two Bivariate Normal distributions:
  - **A**: Mean and covariance matrix defined in the assignment.
  - **B**: Mean and covariance matrix defined in the assignment.
- Plot the two distributions in the same plot and combine them into a single tensor \( X \) as if they were generated from one distribution.

### K-Means Clustering
- Implement the K-Means clustering algorithm using PyTorch’s `pytorch.xyz` libraries.
- Use the unsupervised dataset created by stacking the data points from the two bivariate Gaussian distributions.

### Principal Component Analysis (PCA)
- Replicate the PCA steps using the synthetic dataset created in the previous tasks and PyTorch’s `pytorch.xyz` libraries.

## Directory Structure

- `Assignment1A/`: Contains all code and notebooks for Assignment 1A.
- `README.md`: This file, providing an overview of the assignment.

## Screenshots
- Screenshot of the cloned repository in the terminal.
- Screenshot of the virtual environment setup in the IDE.

## Contact
For any questions or clarifications, feel free to contact me at `NV2375@nyu.edu`.

