# Classification in Python with Scikit-Learn

As the name suggests, Classification is the task of “classifying things” into sub-categories.But, by a machine!

## How does classification works?

Suppose we have to predict whether a given patient has a certain disease or not, on the basis of 3 variables, called features.

Which means there are two possible outcomes:

  1.  The patient has the said disease. Basically a result labelled “Yes” or “True”.
  2.  The patient is disease free. A result labelled “No” or “False”.

This is a binary classification problem.

We have a set of observations called training data set, which comprises of sample data with actual classification results. We train a model, called Classifier on this data set, and use that model to predict whether a certain patient will have the disease or not.

The outcome, thus now depends upon :

  1.  How well these features are able to “map” to the outcome.
  2.  The quality of our data set. By quality I refer to statistical and Mathematical qualities.
  3.  How well our Classifier generalizes this relationship between the features and the outcome.
  4.  The values of the x1 and x2.

# 1. Classfication Intro:

This jupyter notebook contains basics of classification, different types of classification models and their implementation.

Dataset used: Fruits.txt

# 2. Classification Models:

First part of this jupyter notebook contains KNearest Neighbors Classifier Model with different model selectioon like train_test_split and cross validation model. 

Second part of this notebook contains "Fine Tuning of the Model" i.e. how to get Classification Report and Confusion Matrix.

Second part also contains the Hyperparameters like GridSearchCV , RandomizedSearchCV, Ridge Model and How to deal with missing values.

Third part contains the Preprocesssing and Pipeline of the data.

Last part of the jupyter notebook contains basics of another classification model named Support Vector Machines (SVM).

Dataset used: diabetess.csv

# 3. XGBoost Jupyter Notebook:

This jupyter notebook contains Tutorials on XGBoost Model.
