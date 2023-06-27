
# Project Title

In this lab we have performed a complete machine learning process for a simple linear regression model. The same steps are followed for creating and testing any machine learning model. The steps in this process include:

Used weight-height dataset. Detailed data exploration has been performed.



## Agenda
1. In this lab we will apply linear regression modules using the Python scikit-learn package. In particularly;
Understand the basics of applying regression models for prediction.
2. Evaluate the performance of regression models.
Apply a recipe for using scikit-learn to define, train and test machine learning models. Overvie
## Introduction
 Simple linear regression is a great first machine learning algorithm to implement as it requires you to estimate properties from our training dataset.

Linear regression assumes a linear or straight line relationship between the input variables (X) and the single output variable (y). More specifically, that output (y) can be calculated from a linear combination of the input variables (X). When there is a single input variable, the method is referred to as a simple linear regression.In simple linear regression we can use statistics on the training data to estimate the coefficients required by the model to make predictions on new data.
## Goal
he goal is to find the best estimates for the coefficients to minimize the errors in predicting y from x. Simple regression is great, because rather than having to search for values by trial and error or calculate them analytically using more advanced linear algebra, we can estimate them directly from our data. We can start off by estimating the value for B1.
## Analysis of the dataset
The dataset selected contains the height and weight of 5000 males and 5000 females.
## Outcome Summary
In this lab we have performed a complete machine learning process for a simple linear regression model. The same steps are followed for creating and testing any machine learning model. The steps in this process include:

Used weight-height dataset. Detailed data exploration has been performed.
Prepared the data. The dataset divided diveded into to sets using the categorical column Gender. After that data preparation done by splitting the data into training and test subset.
Constructed the regression model using training data with scikit-learn.
Evaluated the results of the model using the test data. In this case the residuals were found to be reasonably small and well behaved.
## Used Libraries
For withdraw insights from the data ,we must have the following python liberies installed to analyse data deeply.

Numpy: NumPy (Numerical Python) is an open source Python library that’s used in almost every field of science and engineering. It’s the universal standard for working with numerical data in Python. https://numpy.org/doc/stable/user/absolute_beginners.html

Pandas: pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language. https://pandas.pydata.org/docs/

Seaborn: Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics. https://seaborn.pydata.org/

Matplotlib: Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. https://matplotlib.org/

Sklearn: Simple and efficient tools for predictive data analysis https://scikit-learn.org/stable/