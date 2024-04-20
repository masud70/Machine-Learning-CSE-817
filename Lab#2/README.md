## Lab#2: Linear Regression, Logistic Regression, and SVM Classification

This folder contains the code implementation for Lab#2 of the Machine Learning 817 course. In this lab, I've explored three powerful algorithms for classification and regression:

* **Linear Regression:** This supervised learning technique models the relationship between a dependent variable (to be predicted) and one or more independent variables (features) using a linear equation. It's suitable for continuous target variables.
* **Logistic Regression:**  Another supervised learning technique, logistic regression predicts the probability of a binary outcome (0 or 1) using a sigmoid function. It's commonly used for classification problems.
* **Support Vector Machine (SVM) Classification:** This supervised learning technique finds a hyperplane in the feature space that best separates the data points of different classes. It maximizes the margin between the hyperplane and the nearest data points (support vectors).

## Content:

* **`linear_regression.ipynb`**: This Python script likely implements the linear regression model explored in the lab. It includes functions for:
    * Importing required libraries
    * Loading the training and testing data
    * Visualizing the training and testing data
    * Training the linear regression model.
    * Making predictions for new data points.
    * Evaluating the model performance.
* **`logistic_regression.ipynb`**: This Python script likely implements the logistic regression model explored in the lab. It includes functions for:
    * Importing required libraries
    * Loading the training and testing data
    * Visualizing the training and testing data
    * Training the logistic regression model.
    * Making predictions for new data points.
    * Evaluating the model performance.
* **`svm_classification.ipynb`**: This Python script likely implements the SVM classification model explored in the lab. It includes functions for:
    * Importing required libraries
    * Loading the training and testing data
    * Visualizing the training and testing data
    * Training the SVM classification model.
    * Making predictions for new data points.
    * Evaluating the model performance.

**Data Files:**

* **`insurance_data.csv`**: The data files used in this lab. This single dataset is used for linear regression and logistic regression models.
* A separate dataset imported from `sklearn.datasets` for classification tasks.

This lab provides an opportunity to compare and contrast different algorithms for various prediction tasks.