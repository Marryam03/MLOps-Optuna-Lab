# Hyperparameter Optimization with Optuna

In this Lab, I utilized Optuna, an automated hyperparameter optimization framework, to enhance the performance of a neural network model for text classification. The process involved the following steps:

1) Data Preparation: Loaded and preprocessed the Reuters dataset, including tokenization and padding of sequences.

2) Model Definition: Created a neural network with multiple layers using PyTorch.

3) Objective Function: Defined an objective function to train and evaluate the model, which Optuna uses to determine the best set of hyperparameters.

4) Hyperparameter Search: Conducted a search over several hyperparameters such as the number of hidden layers, units per layer, dropout rate, and learning rate.

5) Evaluation: Evaluated the best model on the test dataset and achieved an accuracy of 40.61%.

