# Ensemble Learning
This repository contains different implementations of ensemble models using Bagging and Boosting techniques, such as Random Forest, AdaBoost, ...

## AdaBoost
AdaBoost is an ensemble algorithm that combines multiple weak classifiers (such as simple decision trees) to form a strong classifier. It works adaptively by adjusting the weight of each observation based on the errors of the previous model giving more importance to misclassified examples. Each new model is trained with a stronger focus on the previous model's errors, and all models are then combined, with each one weighted according to its metric.

**Activities**

- [AdaBoost implementation using GridSearchCV](https://github.com/Kaiziferr/ensemble_learning/tree/main/boosting/Ada_Boost): Implementation of the AdaBoost model using GridSearchCV

## Random Forest
Random Forest is an ensemble algorithm based on combining multiple independent decision trees. Each tree is trained on a random sample of the dataset and uses a random subset of features to split at each node. The final result is obtained by voting (for classification) or averaging (for regression) across all the trees.

**Activities**

- [Oob Score in Random Forest](https://github.com/Kaiziferr/ensemble_learning/tree/main/bagging/Random_Forest): The goal of this project is to demonstrate the use of out-of-bag (oob) scorein Random Forest, including the standard functions for classification (such as Accuracy) and regression (R²). Additionally, it shows how to implement a custom function with a different metric to be used as a performance criterion for oob score
