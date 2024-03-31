# Red Wine Quality Classification with Random Forest

## Description
This repository implements Random Forest classification to predict the quality of red wine based on physicochemical properties. It leverages the Red Wine Quality dataset from UCI Machine Learning Repository and employs hyperparameter tuning to optimize the Random Forest model's performance.

## Dataset
This project utilizes the Red Wine Quality dataset from the UCI Machine Learning Repository. It contains physicochemical properties of red wine samples along with their quality ratings.\
\
**Source**: UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/wine+quality)\
**Description**: Physicochemical properties of Portuguese "Vinho Verde" red wine samples and their quality ratings.\
**Input variables** (11): Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol.\
**Output variable** (1): Quality score (0-10).

## Key Steps:
### Data Loading and Preprocessing:
Imports necessary libraries.\
Loads the Red Wine Quality dataset.\
Splits the data into training and testing sets.

### Model Training:
Defines a Random Forest Classifier object.\
Sets up a GridSearchCV object with hyperparameter tuning for the number of estimators (n_estimators).\
Trains the model on the training data.

### Evaluation:
Predicts wine quality labels on the testing data using the trained model.\
Calculates and prints the confusion matrix, classification report, and accuracy score to assess model performance.
