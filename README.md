# Project: Predicting Boston Housing Prices
*Predict the selling price of a new home in the Boston, Massachusetts area.*
### For Udacity's Machine Learning Engineer Nanodegree
<img src="https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/mlndlogo.png" height="140">

### Topic: Model Evaluation and Validation

### Overview:

* I defined a performance metric and used K-Fold cross validation to compare various Decision Tree regressor models to find the one that does the best job predicting selling prices of new homes in the Boston, Massachusetts housing market.
* My dataset contains 506 entries with 14 features that represent aggregated data for homes in Boston. It was collected in 1978 and comes from the [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Housing).

### Concepts:

* Using Pandas to explore and preprocess a real-world dataset that contains missing values, outliers, and various other idiosyncrasies.
* Shuffling and splitting a dataset into training and testing sets, in order to evaluate a model's performance on unseen data.
* Defining a performance metric to evaluate a model's performance. I use R^2, the [coefficient of determination](https://en.wikipedia.org/wiki/Coefficient_of_determination).
* Visually depicting a model's learning performance with learning curves, and using complexity curves to observe the tradeoff between bias (underfitting) and variance (overfitting).
* Training a Decision Tree regressor from Scikit-Learn that generalizes to unseen data.
* Finding the best performing hyperparameters by using GridSearch and K-Fold cross validation.
* Conducting sensitivity analysis on a fully-trained model.

### My completed project:

* [ipython notebook](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/boston_housing.ipynb) / [html version](http://htmlpreview.github.com/?https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/report.html) / [pdf version](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/boston_housing.pdf)

### Project Grading and Evaluation:

* [Project Review](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/boston_housing_project_review.pdf)

* [Project Grading Rubric](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/boston_housing_project_grading_rubric.pdf)

### Dependencies:

* [requirements.txt](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/requirements.txt)

* [Anaconda .yml file](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/boston_housing_project.yml)
