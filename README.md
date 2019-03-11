# Bayesian_hyperparam_optimization


Hyperparameter search in supervised learning tasks is both computationally expensive and time consuming. Two common approaches are grid search and random search. Bayesian hyperparameter search makes use of previous evaluations of hyperparameters in order to smarter test new configurations of hyperparameters. For more details on bayesian optimization see the following paper https://arxiv.org/pdf/1807.02811.pdf.

In this notebook we use bayesian optimization to optimize hyperparameters for a binary classification problem. The optimization is done for a gradient boosting model but the code can easily be modified to work with any other model.
