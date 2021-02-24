# Linear Regression in Python with Scikit-Learn

In statistics, **linear regression** is a linear approach to modelling the relationship between a scalar response and one or more explanatory variables (also known as dependent and independent variables). The case of one explanatory variable is called simple linear regression; for more than one, the process is called multiple linear regression. [(Wikipedia)](https://en.wikipedia.org/wiki/Linear_regression)

Must read this blog - https://machinelearningmastery.com/linear-regression-for-machine-learning/ 

Linear regression is a linear model, e.g. a model that assumes a linear relationship between the input variables (x) and the single output variable (y). More specifically, that y can be calculated from a linear combination of the input variables (x).

When there is a single input variable (x), the method is referred to as **simple linear regression**. When there are multiple input variables, literature from statistics often refers to the method as **multiple linear regression**.

Different techniques can be used to prepare or train the linear regression equation from data, the most common of which is called **Ordinary Least Squares**. It is common to therefore refer to a model prepared this way as Ordinary Least Squares Linear Regression or just Least Squares Regression.

---
## Implementing Linear Regression Algorithm - 
There are five basic steps when you’re implementing linear regression:

  - Import the packages and classes you need.
  - Provide data to work with and eventually do appropriate transformations.
  - Create a regression model and fit it with existing data.
  - Check the results of model fitting to know whether the model is satisfactory.
  - Apply the model for predictions.
 
---
## Sub-sections

  - **Introduction**
  - **Advanced**

---
### [Introduction](https://github.com/Ravjot03/Machine-Learning-Models/tree/master/Regression%20Models/Linear%20Regression/Introduction)

In this sub-part, I have explained how to implement a Simple Linear Regression Model and do predictions.

---
### [Advanced](https://github.com/Ravjot03/Machine-Learning-Models/tree/master/Regression%20Models/Linear%20Regression/Advanced)
In this sub-part, I have explained implementation of different types of linear regression model - 
  
  - Implemented Simple Linear Regression Model
  - Applied Cross Validation to estimate our model's accuracy.
  - Applied Regularized Regression Models
    - Ridge Regression Model
    - Lasso Regression Model
  - Pre-processing data and Hyperparameters tuning
    - SimpleImputer, StandardScaler
    - Elastic Net Regularization Regression 

I have worked on [Gapminder Data](https://www.gapminder.org/), to predict the life expectancy in a given country based on features such as the country's GDP, fertility rate, and population.
