# ensemble_learning
This repository contains different implementations of ensemble models using Bagging and Boosting techniques, such as Random Forest, AdaBoost, ...

## AdaBoost
AdaBoost is an ensemble algorithm that combines multiple weak classifiers (such as simple decision trees) to form a strong classifier. It works adaptively by adjusting the weight of each observation based on the errors of the previous model giving more importance to misclassified examples. Each new model is trained with a stronger focus on the previous model's errors, and all models are then combined, with each one weighted according to its metric.

**Activities**

- [AdaBoost implementation using GridSearchCV](https://github.com/Kaiziferr/ensemble_learning/tree/main/boosting/Ada_Boost) 
