# Model Selection and Hyper-parameters Tuning

This repository contains the solution for an assignment focusing on model selection and hyper-parameter tuning using Python. Two distinct tasks are addressed: Polynomial Regression and Logistic Regression.

## Polynomial Regression

### 1. Dataset Information
- The `data_reg.csv` file consists of 200 examples with attributes x1 and x2 and a continuous target label y.

### 2. Tasks

1. **Data Splitting and Visualization**
   - Read the data from the CSV file and split it into training, validation, and testing sets.
   - Plot the examples from the three sets in a 3D scatter plot, where x and y represent x1 and x2 features, and the z-axis is the target label y.

2. **Polynomial Regression**
   - Apply polynomial regression on the training set with degrees ranging from 1 to 10.
   - Identify the best polynomial degree by plotting the validation error vs polynomial degree curve.
   - Plot the surface of the learned function alongside the training examples for each model.

3. **Ridge Regression**
   - Apply ridge regression on the training set to fit a polynomial of degree 8.
   - Choose the best regularization parameter from options {0.001, 0.005, 0.01, 0.1, 10}.
   - Plot the Mean Squared Error (MSE) on the validation vs the regularization parameter.

### Logistic Regression

1. **Data and Model Learning**
   - The `train_cls.csv` file contains training examples for a binary classification problem.
   - Use the logistic regression implementation from scikit-learn to learn a model with a linear decision boundary.
   - Draw the decision boundary on a scatterplot of the training set and compute the training and testing accuracy.

2. **Quadratic Decision Boundary**
   - Repeat part 1 to learn a logistic regression model with a quadratic decision boundary.

3. **Model Evaluation**
   - Comment on the learned models in terms of overfitting/underfitting.


Feel free to explore the provided code and report to understand the analysis conducted on the datasets and the insights obtained.
