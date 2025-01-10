# CS-GY-6613 Assignment 2A
## Submission by: Naman Vashishta (NV2375 N11740506)

This repository contains the code and documentation for **Assignment 2A** of CS-GY-6613. In this assignment, you will implement explainer algorithms to understand the decision-making process of a Convolutional Neural Network (CNN) trained for the **cats vs. dogs classification task**.

## Assignment Tasks

### Anomaly Detection: CNN Explainers
- You will implement two explainer algorithms to interpret the model’s decisions:
  - **Integrated Gradients**: This method attributes the prediction of a model to the input features by computing the gradients of the output with respect to the input along the path from a baseline (e.g., black image) to the actual input.
  - **Grad-CAM (Gradient-weighted Class Activation Mapping)**: This method highlights regions of the input image that were important for the model’s decision, by computing the gradients of the target class with respect to the final convolutional layer’s feature map.

- It is recommended to implement the assignment using **PyTorch** and **Captum** for these explainer algorithms.

### Requirements
- Your notebook should provide a detailed explanation of the explainer methods in a tutorial fashion so that anyone with a basic understanding of CNNs can follow.
- The notebook should also include the results of each explainer algorithm applied to the **cats vs. dogs classification task**.
- Data augmentation was used during model training, and the model has achieved a certain level of accuracy without overfitting.

## Directory Structure

- `Assignment2A/`: Contains all code and notebooks for Assignment 2A.
- `README.md`: This file, providing an overview of the assignment.

## Screenshots
- Screenshots of the results from the Integrated Gradients and Grad-CAM explainer algorithms applied to the model.

## Contact
For any questions or clarifications, feel free to contact me at `NV2375@nyu.edu`.

