# RegressionAnalysis
The aim of the work is to acquaint oneself with the fundamentals of regression analysis, the linear regression model, and its recovery procedure. This will enable me to acquire skills in recovering this model using real data.


This project aims to perform regression analysis on a given dataset - Abalone(https://archive.ics.uci.edu/ml/datasets/abalone). Among the indicators in the dataset, there is one that needs to be predicted based on the others. This indicator is referred to as the dependent or target variable.

Within the scope of this lab work, the following steps should be taken to restore a linear regression model for predicting the dependent variable:

Data Preparation:

Handle missing values by either removing corresponding rows or filling gaps using appropriate methods such as mean or median values.
Consider removing a certain indicator if a significant portion of its values is missing.
If qualitative indicators are present, transform them into binary dummy variables.
Build a Simple Linear Regression:

Identify the indicator that correlates most strongly with the dependent variable.
Build a one-dimensional linear regression model based on the strongest indicator.
Plot the restored regression line along with the correlation plot.
Calculate the residual variance of the regression.
Test the significance of regression parameters and the model itself.
Assess model adequacy using the coefficient of determination and the appearance of the regression line plot alongside the correlation field.
Construct a Multivariate Linear Regression:

Build a linear regression model using all available indicators.
Compute the residual variance.
Test the significance of regression parameters and the model itself.
Analyze the significance of individual parameters. Is every parameter significant?
Evaluate model adequacy. If the model is significant, check its adequacy by calculating the coefficient of determination, checking residual distribution normality, and analyzing the residual plot.
Construct a learning curve to assess overfitting and whether there are enough data points for a well-generalized model.
Attempt to Build a Simpler or More Adequate Model:

If certain parameters of the multivariate linear regression are insignificant, remove them and re-evaluate the model's quality. Has the quality changed significantly? Could you have removed indicators that were part of a multicollinear group?
Detect multicollinear groups by analyzing the Pearson correlation coefficient matrix and the Variance Inflation Factor (VIF).
If found, eliminate redundant indicators from the group and rebuild the linear regression without them. Consider using regularization techniques.
If indicators display significant left-skewed distribution, nonlinear relationships in correlation plots, or nonlinearity in residual plots, consider transforming the indicators (e.g., logarithmic transformation), rebuild the model, and assess its quality.
