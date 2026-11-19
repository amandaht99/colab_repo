# Titanic Survival — Neural Network Hyperparameter Search

SE_14 extended task: hyperparameter search for a Keras dense NN on the Titanic dataset. Full procedure and results are documented in the notebook's "Experiment Results" cell.

Baseline: 1 hidden layer, 2 neurons, relu, sgd, 50 epochs. Accuracy 0.676, precision 0.674, recall 0.397, F1 0.500.

Final model: 1 hidden layer, 8 neurons, relu, sgd, 50 epochs, class-weighted, threshold 0.45. Accuracy 0.771, precision 0.722, recall 0.712, F1 0.717.
