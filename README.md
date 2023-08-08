# RegressionAnalysis
The aim of the work is to acquaint oneself with the fundamentals of regression analysis, the linear regression model, and its recovery procedure. This will enable me to acquire skills in recovering this model using real data.


This project aims to perform regression analysis on a given dataset - Abalone(https://archive.ics.uci.edu/ml/datasets/abalone). Among the indicators in the dataset, there is one that needs to be predicted based on the others. This indicator is referred to as the dependent or target variable.

I have completed the project task which involved working with a given dataset, similar to the previous task. Among the variables in the dataset, there is one that needs to be predicted based on other variables. This variable is the dependent or target variable.

The main objective of the project was to build a linear regression model to predict the dependent variable using other variables as predictors. The following steps were involved in completing the project:

1. Data Preparation: I prepared the data for regression analysis. I handled missing values by either removing corresponding rows or filling in the missing values with mean or median values of the respective variable. For categorical variables, I transformed them into binary dummy variables.

2. One-Dimensional Linear Regression: I identified the variable that had the strongest correlation with the dependent variable and built a one-dimensional linear regression model based on that correlation. I visualized the regression line along with the correlation field. I calculated the residual variance of the regression and checked the significance of regression parameters and the model itself. The adequacy of the model was determined based on the coefficient of determination and the appearance of the regression line and correlation field.

3. Multi-Dimensional Linear Regression: I built a multi-dimensional linear regression model using all available predictors. I calculated the residual variance and tested the significance of regression parameters and the model itself. I assessed whether all parameters were significant and whether the model was significant. If the model was significant, I checked its adequacy by calculating the coefficient of determination, checking the normality of residuals, and analyzing residual plots. I also examined the learning curve to evaluate overfitting and the sufficiency of data for building a reliable model.

4. Simplifying the Model: I attempted to build a simpler or more adequate regression model by performing the following steps:
   - If any parameters from the multi-dimensional linear regression were found to be insignificant, I removed them and assessed the new model's quality.
   - I investigated multicollinearity by analyzing the correlation matrix and using the variance inflation factor (VIF). If multicollinearity was detected, I removed correlated predictors or applied regularization techniques.
   - If there were variables with significantly skewed distributions or if nonlinear relationships were observed on correlation plots or residual plots, I applied transformations (e.g., logarithmic) to the variables and evaluated the quality of the new model.


The second part of the project required me to write two custom functions.

The first function takes a two-dimensional dataset (consisting of two variables - x and y) as input, performs a one-dimensional linear regression based on this data, and checks its adequacy. The function outputs the following results:
- A table with estimated regression parameters, coefficient of determination,
- Results of the F-test in terms of statistics and p-value,
- Residual variance,
- Residual histogram,
- Shapiro-Wilk test results for normality of residuals,
- Correlation field plot with the regression line, confidence intervals on regression, and predicted values.

The second function takes a multi-dimensional dataset (with one dependent variable and all others as independent variables) as input, builds a multi-dimensional linear regression based on this data, and checks its adequacy. The function also accepts a boolean parameter "interception" (if True, the model is built with an intercept term; otherwise, without an intercept term). The function outputs the following results:
- A table with estimated regression parameters, coefficient of determination,
- Results of the F-test in terms of statistics and p-value,
- Residual variance,
- Residual histogram,
- Shapiro-Wilk test results for normality of residuals,
- Residuals diagram (with predicted values of the dependent variable along the horizontal axis and residuals along the vertical axis).

In both cases, these functions are designed to automate the process of regression analysis and adequacy testing for different types of linear regression models. They provide a comprehensive set of visualizations and statistical tests to assess the quality and appropriateness of the models.


