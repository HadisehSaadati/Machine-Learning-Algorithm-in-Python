# Machine Learning Algorithms in Python

> This repository contains a ***Jupyter Notebook exploring fundamental machine learning algorithms and concepts using Python and Scikit-learn***. The notebook uses the **Iris dataset** to practice **classification**, **regression**, **model evaluation**, and **cross-validation**. It also includes a simple **linear regression** example with manually defined data to illustrate how a regression model learns relationships between variables. The project serves as a hands-on introduction to implementing machine learning algorithms, training models, and evaluating their predictive performance.

## 1. Data Exploration and Preparation

- Loading the Iris dataset using Scikit-learn.
- Exploring dataset features and target labels.
- Converting the dataset into a pandas DataFrame.
- Examining relationships between input features.


## 2. K-Nearest Neighbors (KNN)

- Implementing a KNN classifier.
- Making predictions for new samples.
- Splitting the dataset into training and testing sets.
- Evaluating classification accuracy.
- Investigating how the number of neighbors affects training and testing accuracy.

## 3. Linear Regression

- Implementing linear regression on a small, manually defined dataset.
- Fitting a regression model to observed data.
- Generating predictions using the fitted model.


## 4. Model Evaluation

- Splitting data into training and testing sets.
- Calculating Mean Squared Error (MSE).
- Evaluating regression predictions against the target values.

## 5. K-Fold Cross-Validation

- Applying cross-validation with five folds.
- Examining cross-validation scores.
- Calculating the mean score across folds.

## 6. Lasso Regression

- Fitting a Lasso regression model.
- Examining regression coefficients.
- Evaluating predictions using Mean Squared Error.

## 7. Ridge Regression

- Fitting a Ridge regression model.
- Evaluating its predictions using Mean Squared Error.
- Exploring regularized linear regression as a machine learning technique.

# Dataset

The notebook uses the Iris dataset, a classic dataset for introductory machine learning.

It contains measurements of iris flowers across four features:

- Sepal length
- Sepal width
- Petal length
- Petal width

The target variable represents three Iris species:

- Setosa
- Versicolor
- Virginica

**The dataset is loaded directly from Scikit-learn, so no separate dataset download is required.**
