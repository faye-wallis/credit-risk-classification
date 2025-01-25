# Data Analytics Bootcamp Challenge #20

## Overview of the Analysis

* The purpose of this analysis is to predict the relative health of a loan based upon a list of defining features.
* The model used for this analysis was trained on a dataset of roughly 78,000 recorded loans.
* The features analyzed by this model include the size and interest rate of each loan, the borrower's income level, total debt, and the ratio between them, as well as the number of accounts held by the borrower, and their number of derogatory remarks.
* To perform the analysis, I separated the source data into that list of defining features, and the target metric we hoped to predict with them. Each variable was then further separated into training and test data, helping the model to serve its intended purpose of making predictions based on incomplete data. From there, I instantiated our Linear Regression model, fit it to the training data, and output our first set of predictions.
* The Linear Regression model creates these predictions by examining our training data and calculating a line of best fit that passes through it. The formula for that line can then be applied to make predictions of new data when it is introduced.

## Results

- Precision (Healthy): 100%
- Precision (High-Risk): 87%
- Recall (Healthy): 100%
- Recall (High-Risk): 95%
- Accuracy (Overall): 99%

## Summary
With these results, we can see that the linear nature of this data fits well with our Linear Regression model. There is some room to improve with the precision of our High-Risk predictions, for which I would recommed applying Standard Scaling to our feature data in future iterations. Otherwise, this model is highly accurate and suitable for use.