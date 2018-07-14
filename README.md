# Project: Predicting Boston Housing Prices
*Predict the selling price of a new home in the Boston, Massachusetts area.*
### For Udacity's Machine Learning Engineer Nanodegree
<img src="https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/mlndlogo.png" height="140">

### Topic: Model Evaluation and Validation

### Overview:

* I trained a Decision Tree regressor to predict the selling prices of homes in the Boston, Massachusetts housing market.
* The dataset contains 506 entries with 14 features that represent aggregated data for homes in Boston. It was collected in 1978 and comes from the [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Housing).

### Concepts:

* Using Pandas to explore a real-world dataset, that contains missing values, outliers, and various other idiosyncrasies.
* Shuffling and splitting a dataset into training and testing sets.
* Defining a performance metric to evaluate a model's performance. I use $R^{2}$, the coefficient of determination.
* Visually depicting a model's performance with learning curves, and using complexity curves to observe the tradeoff between bias (underfitting) and variance(overfitting).
* Training a Decision Tree regressor from Scikit-Learn that generalizes to unseen data.
* Finding the best performing hyperparameters with GridSearch and K-Fold cross validation.
* Conducting sensitivity analysis on a fully-trained model.

### My completed project:

* [ipython notebook](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/boston_housing.ipynb) / [html version](http://htmlpreview.github.com/?https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/report.html) / [pdf version](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/boston_housing.pdf)

### Project Grading and Evaluation:

* [Project Review](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/boston_housing_project_review.pdf)

* [Project Grading Rubric](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/boston_housing_project_grading_rubric.pdf)

### Dependencies:

* [requirements.txt](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/requirements.txt)

* [Anaconda .yml file](https://github.com/jamesdellinger/machine_learning_nanodegree_boston_housing_project/blob/master/boston_housing_project.yml)

## Project Overview
 Next, you will properly split the data into testing and training subsets, and determine a suitable performance metric for this problem. You will then analyze performance graphs for a learning algorithm with varying parameters and training set sizes. This will enable you to pick the optimal model that best generalizes for unseen data. Finally, you will test this optimal model on a new sample and compare the predicted selling price to your statistics.

## Project Highlights
This project is designed to get you acquainted to working with datasets in Python and applying basic machine learning techniques using NumPy and Scikit-Learn. Before being expected to use many of the available algorithms in the sklearn library, it will be helpful to first practice analyzing and interpreting the performance of your model.

Things you will learn by completing this project:

- How to use NumPy to investigate the latent features of a dataset.
- How to analyze various learning performance plots for variance and bias.
- How to determine the best-guess model for predictions from unseen data.
- How to evaluate a model's performance on unseen data using previous data.
