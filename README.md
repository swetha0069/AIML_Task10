# Task 10: KNN - Handwritten Digit Classification

## Project Overview
This project implements a **K-Nearest Neighbors (KNN)** machine learning model to classify handwritten digits (0-9). Using the `load_digits` dataset from Scikit-learn, the model identifies patterns in 8x8 pixel images to predict the correct numerical label.

## Workflow
* **Data Loading:** Loaded the Sklearn Digits dataset and verified its structure.
* **Visualization:** Displayed sample images to understand pixel-to-label mapping.
* **Preprocessing:** Applied `StandardScaler` to normalize data, which is essential for distance-based algorithms like KNN.
* **Hyperparameter Tuning:** Evaluated the model using multiple K values (3, 5, 7, 9).
* **Evaluation:** Generated an **Accuracy vs. K** plot and a **Confusion Matrix** to analyze misclassifications.

## Key Technical Findings
* **Best K Value:** $K=3$ provided the optimal balance of accuracy and generalization.
* **Distance Metric:** Used Euclidean distance to measure similarity between pixel vectors.
* **Scaling Impact:** Scaling is critical; without it, feature variance would skew the distance calculations and reduce accuracy.



## Tools Used
* **Language:** Python
* **Libraries:** Scikit-learn, Matplotlib, NumPy
