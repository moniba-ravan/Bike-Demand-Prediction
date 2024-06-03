# Bike Demand Prediction

## Overview
In this project, we delve into the binary classification challenge of predicting bicycle demand in Washington D.C. Utilizing a robust dataset of 1600 instances, our analysis encompasses the training and fine-tuning of various classifiers, including Logistic Regression, KNN, QDA, LDA, Random Forest, and Bagging. We emphasize understanding the mathematical underpinnings of these models and strategically tuning their hyperparameters. Each model is rigorously evaluated using metrics such as accuracy, F1-score, and ROC, within a cross-validation framework. Our comparative analysis identifies Random Forest as the most effective classifier. 

## Classification methods
- **Logistic Regression**: Utilizes the logistic sigmoid function to calculate the probability of each class. Hyperparameters are tuned using GridSearchCV.
- **LDA and QDA**: Bayes Theorem-based classifiers assuming different covariance matrices for classes. Hyperparameters are tuned using grid search methods.
- **K-nearest neighbor**: Employs the k-NN algorithm to measure distances between data points. Hyperparameters are optimized using a grid search method combined with PCA.
- **Random Forest**: An ensemble method combining decision trees with randomness. Hyperparameters are tuned for both decision trees and Random Forest ensemble.
