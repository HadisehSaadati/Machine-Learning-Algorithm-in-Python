# Machine Learning Algorithms in Python

> This repository contains practical exercises on fundamental machine learning algorithms implemented in Python using Scikit-learn. It covers both ***supervised*** and ***unsupervised learning***, along with **model evaluation**, **cross-validation**, and **hyperparameter optimization**. The notebook applies different algorithms to the Iris and Breast Cancer Wisconsin datasets and explores their use through model fitting, prediction, evaluation, and visualization.

# Data Preparation

- Loading and exploring datasets using Scikit-learn
- Inspecting features, target labels, and dataset structure
- Creating and manipulating datasets with Pandas
- Splitting data into training and test sets

## Supervised Learning

- [x] Classification
- [x] K-Nearest Neighbors (KNN)
- [x] Logistic Regression
- [x] Decision Trees
- [x] Gaussian Naive Bayes
- [x] Multi-Layer Perceptron (MLP) Neural Networks
- [x] Regression
- [x] Linear Regression
- [x] Lasso Regression
- [x] Ridge Regression

## Unsupervised Learning

- [x] Clustering Algorithms
- [x] K-Means Clustering
- [x] Hierarchical Clustering
- [x] Mean Shift
- [x] DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

The clustering exercises include cluster visualization and exploration of model properties, such as K-Means inertia and hierarchical clustering dendrograms.

### Model Evaluation and Validation

- Train-test splitting
- Accuracy scoring
- Confusion matrices
- Classification reports
- Mean Squared Error (MSE)
- K-Fold Cross-Validation
- ROC curve and ROC-AUC analysis

### Hyperparameter Optimization

- Grid Search Cross-Validation (GridSearchCV)
- Randomized Search Cross-Validation (RandomizedSearchCV)
- Exploring the effect of the number of neighbors in KNN
- Tuning selected model parameters

# Datasets

The notebook uses the following datasets available through Scikit-learn:

- **Iris Dataset**: Used for classification, regression exercises, and clustering.
- **Breast Cancer Wisconsin Dataset**: Used for binary classification and model evaluation.

A small manually defined dataset is also used to demonstrate linear regression.
