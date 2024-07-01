# neural-network-challenge-2

# Employee Attrition and Department Prediction

## Overview
This project aims to build a neural network model to predict employee attrition and department using a dataset of employee attributes. The model is designed with two branches: one for predicting attrition and the other for predicting the department.

## Dataset
The dataset includes various attributes of employees such as age, education, job satisfaction, and more. The target variables are:

Attrition (Yes/No)
Department (Sales, Research & Development, Human Resources)


## Steps
### Data Preparation
We prepare the data by encoding categorical variables and scaling numerical features.

### Model Building
We build a neural network with two branches: one for predicting attrition and another for predicting department.

### Model Training
We train the model using the prepared data.

### Model Evaluation
We evaluate the model and print the accuracy for both attrition and department predictions.

## Metrics Explanation
Precision
Precision is the ratio of correctly predicted positive observations to the total predicted positives.
Formula: Precision = True Positives / (True Positives + False Positives)

Recall
Recall is the ratio of correctly predicted positive observations to all observations in the actual class.
Formula: Recall = True Positives / (True Positives + False Negatives)

## Possible Improvements
Use cross-validation for more reliable evaluation.
Experiment with different architectures or hyperparameters.


## Conclusion
This project demonstrates how to build a neural network with multiple branches to predict different targets. The provided code can be further enhanced by tuning hyperparameters, balancing the dataset, and exploring different model architectures.