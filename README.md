# Bagging-Boosting-Stacking-Using-Indian-diabetes-dataset
This code is an example of using different ensemble learning techniques for classification problems.

The first technique used is Bagged Decision Trees. In this technique, a collection of decision tree models are trained on different subsets of the training data, and the predictions from all the models are combined to make the final prediction.

The second technique used is Random Forest Classification. This is similar to Bagged Decision Trees, but instead of using the same decision tree model for each subset of the data, a collection of randomized decision trees are used.

The third technique used is AdaBoost Classification. In this technique, a collection of weak learners (e.g., decision trees with low depth) are trained on the training data, and each weak learner is assigned a weight based on its accuracy. The predictions from all the weak learners are combined to make the final prediction.

The fourth technique used is Stacking Ensemble for Classification. In this technique, multiple models with different learning algorithms are trained on the same data, and their predictions are combined using a meta-learner (e.g., logistic regression) to make the final prediction.

Overall, the code reads in a diabetes dataset, splits the data into input features and output targets, and applies each ensemble learning technique using cross-validation to estimate the model's performance. The average performance across all the folds is printed to the console.
