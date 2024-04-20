# Lab#1: K-means Clustering Algorithm

This folder contains the code implementation for Lab#1 of the Machine Learning 817 course. In this lab, I've explored the **K-Means Clustering Algorithm** and **K-Nearest Neighbors (KNN) algorithm**.

* **K-Means Clustering** is an unsupervised learning technique that groups unlabeled data points into a predefined number of clusters (k). It iteratively assigns data points to the nearest cluster centroid (center) and recomputes the centroids based on the assigned points. This process continues until convergence is achieved, or a stopping criterion is met.
* **KNN** is a supervised learning technique for classification and regression tasks. It classifies new data points based on the labels of their **k-Nearest Neighbors** in the training data. The distance metric (e.g., Euclidean distance) is used to determine how "close" data points are in the feature space.

## Content:

* **`kmeans.ipynb`**: This Jupyter Notebook implements the K-means Clustering Algorithm explored in the lab. It includes functions for:
    * Importing required libraries
    * Loading the training and testing data
    * Visualizing the training and testing data
    * Training the K-means Clustering model.
    * Making predictions for new data points.
    * Evaluating the model performance.
* **`knn.ipynb`**: This Jupyter Notebook implements the KNN algorithm explored in the lab. It includes functions for:
    * Importing required libraries
    * Loading the training and testing data
    * Visualizing the training and testing data
    * Training and testing the model
    * Making predictions for new data points using KNN classification.
    * Evaluating the model performance.

## Data Files:

* **`income.csv`**: This CSV file contains the dataset used in this Lab for implementing the **K-Means Clustering** algorithm. It includes features relevant to income clustering.
* All the data required for training and testing in the **KNN** model implementation is imported from the `sklearn.datasets` directory.