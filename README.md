# Do we need more bikes?

## Overview
In this project, we delve into the binary classification challenge of predicting bicycle demand in Washington D.C. Utilizing a robust dataset of 1600 instances, our analysis encompasses the training and fine-tuning of various classifiers, including Logistic Regression, KNN, QDA, LDA, Random Forest, and Bagging. We emphasize understanding the mathematical underpinnings of these models and strategically tuning their hyperparameters. Each model is rigorously evaluated using metrics such as accuracy, F1-score, and ROC, within a cross-validation framework. Our comparative analysis identifies Random Forest as the most effective classifier.

## Classification Methods
- **Logistic Regression**: Utilizes the logistic sigmoid function to calculate the probability of each class. Hyperparameters are tuned using GridSearchCV.
- **LDA and QDA**: Bayes Theorem-based classifiers assuming different covariance matrices for classes. Hyperparameters are tuned using grid search methods.
- **K-nearest Neighbor**: Employs the k-NN algorithm to measure distances between data points. Hyperparameters are optimized using a grid search method combined with PCA.
- **Random Forest**: An ensemble method combining decision trees with randomness. Hyperparameters are tuned for both decision trees and the Random Forest ensemble.

## Folder Structure
- `Data/`
  - `training_data.csv`: File containing the dataset used for training the machine learning models.
  - `test_data.csv`: File containing the test dataset for making predictions.

## Copyright and Usage
This project was developed as part of the course *Statistical Machine Learning* at Uppsala University.

Authors:
-  Chen Gu 
-  Nora Derner
-  Saba Yousefi
-  S.Moniba Ravan 

This code is intended for educational purposes only. Redistribution or use of this code beyond personal or academic reference must include proper attribution to the original authors.

© 2023 S.Moniba Ravan, Saba Yousefi, Nora Derner, Chen Gu. All rights reserved.
