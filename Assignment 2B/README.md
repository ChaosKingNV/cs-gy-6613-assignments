# CS-GY-6613 Assignment 2B
## Submission by: Naman Vashishta (NV2375 N11740506)

This repository contains the code and documentation for **Assignment 2B** of CS-GY-6613. In this assignment, you will work on anomaly detection using the **MVTec-AD dataset**, applying two models, **PatchCore** and **EfficientAD**, to detect anomalies in specific object categories.

## Assignment Tasks

### Anomaly Detection using the MVTec-AD Dataset
- **Dataset Overview**: The MVTec Anomaly Detection (MVTec-AD) dataset contains images of 15 object categories, including defects like scratches, dents, and discoloration. For this assignment, you will focus on object categories that involve flat surfaces: **tile**, **leather**, and **grid**.
- **Types of Anomalies**: The anomalies can be structural (e.g., scratches, missing parts) or textural (e.g., discoloration, irregular patterns).
- **Class Imbalance**: The dataset has more normal (non-defective) samples than defective ones, which mirrors real-world anomaly detection problems.

### Models to Implement
- **PatchCore**: This model will be used for anomaly detection in the dataset.
- **EfficientAD**: Another model for anomaly detection that will be applied to the dataset.
- You will report **AUROC** scores for both models at the product category level and the average across categories.

### Results and Report
- **AUROC Scores**: You need to report the AUROC (Area Under Receiver Operating Characteristic curve) scores for both models.
- **Documentation**: Your report should explain the models and the results, including the use of the **anomalib** library for anomaly detection. The paper should be tutorial-like, explaining how to use the library and how the models work, including a detailed explanation of any technical terms such as **coresets**.

### Similarity Search
- **Feature Extraction**: Extract features from the models and perform similarity search on anomalous cases predicted by the models.
- **Qdrant Vector Database**: Use the Qdrant vector database to store features and perform similarity search. The code should accept an image and return the top 5 similar images. If an image is an anomalous case, the similar images should also be anomalous.

## Requirements
- **anomalib library**: This library simplifies the process of anomaly detection, offering tools for data preprocessing, model training, and evaluation.
- **PyTorch**: For implementing and training the models.

## Directory Structure

- `Assignment2B/`: Contains all code and notebooks for Assignment 2B.
- `README.md`: This file, providing an overview of the assignment.

## Screenshots
- Screenshots of AUROC scores, anomaly detection visualizations, and similarity search results.

## Contact
For any questions or clarifications, feel free to contact me at `NV2375@nyu.edu`.

