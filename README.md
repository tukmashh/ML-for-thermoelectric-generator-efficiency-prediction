Model for thermoelectric generator efficiency (TEG) prediction.

Descriptors: physical properties of thermoelectric materials and engineering parameters of TEG.

Model uses gradient boosting based on decision trees to find the most important features, forming the selected features.

For final model we use selected features and hyperparameters optimization via optuna library.

Genetic algorithm is used to optimise the values of selected features via the maximization of TEG efficiency function.
