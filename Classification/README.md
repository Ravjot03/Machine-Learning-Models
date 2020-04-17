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
