# Regression Models

## What is Regression Analysis ?
Regression analysis is a predictive modelling technique that analyzes the relation between the target or dependent variable and independent variable in a dataset. This technique is used for forecasting, time series modelling and finding the causal effect relationship between the variables.

Regression analysis is an important tool for modelling and analyzing data. Here, we fit a curve / line to the data points, in such a manner that the differences between the distances of data points from the curve or line is minimized.

## Types of Regression Analysis Techniques

There are many types of regression analysis techniques, and the use of each method depends upon the number of factors. These factors include the type of target variable, shape of the regression line, and the number of independent variables. 

Below are the different regression techniques:

1. **Linear Regression**
2. **Logistic Regression**
3. **Ridge Regression**
4. **Lasso Regression**
5. **Polynomial Regression**
6. **Bayesian Linear Regression**

---

## [1. Linear Regression](https://github.com/Ravjot03/Machine-Learning-Models/tree/master/Regression%20Models/Linear%20Regression)

Linear regression is one of the most basic types of regression in machine learning. The linear regression model consists of a predictor variable and a dependent variable related linearly to each other. In case the data involves more than one independent variable, then linear regression is called multiple linear regression models. 

It is one of the most widely known modeling technique. Linear regression is usually among the first few topics which people pick while learning predictive modeling. In this technique, the dependent variable is continuous, independent variable(s) can be continuous or discrete, and nature of regression line is linear.

Linear Regression establishes a relationship between dependent variable (Y) and one or more independent variables (X) using a best fit straight line (also known as regression line).

The below-given equation is used to denote the linear regression model:

`y=mx+c+e`

**where m is the slope of the line, c is an intercept, and e represents the error in the model.**

![image](https://user-images.githubusercontent.com/34947492/109378388-17b6a380-78f8-11eb-9a9d-7208d0dbc3f5.png)

[Image Source: Analytics Vidhya](https://www.analyticsvidhya.com/blog/)

### How to obtain the best fit line ?

This task can be easily accomplished by **Least Square Method**. It is the most common method used for fitting a regression line. It calculates the best-fit line for the observed data by minimizing the sum of the squares of the vertical deviations from each data point to the line. Because the deviations are first squared, when added, there is no cancelling out between positive and negative values.

### Points to remember:

1. There must be linear relationship between independent and dependent variables.
2. Linear Regression is very sensitive to Outliers. It can terribly affect the regression line and eventually the forecasted values.
3. Multiple regression suffers from multicollinearity, autocorrelation, heteroskedasticity.
4. Multicollinearity can increase the variance of the coefficient estimates and make the estimates very sensitive to minor changes in the model. The result is that the coefficient estimates are unstable.


