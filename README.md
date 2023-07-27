# credit-risk-classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis and what we are trying to analyze.
We are creating predictive model to search through our data and determine which loans are high-risk and which ones are normal, by looking at different factors like dept-to-income. 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
We are predicting future loans investments, trying to determine which loans are high_risk and which loans are standard. 

* Describe the stages of the machine learning process you went through as part of this analysis.
- First we split the data between test and train for bot x and y values
- Second we fit the model with the data, 
- Third we creadte a prediction model with the test data 
- Fourth we create a confussionmatrix ti analzye the data split
- Lastly we run the predictions model. 

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

Logistic Regression uses the data at hand and and turns it into a binary output that separates the outcome on 0 and 1, or true or false. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

* Balanced accuracy report: 0.99
* Presicion Score (Healthy loan): 1.00
* Recall score (Healthy Loan): 0.99
* Presicion Score (High-risk Loan): 0.85
* Recall score (High-risk Loan): 0.91

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

* Balanced accuracy report: 0.99
* Presicion Score (Healthy loan): 1.00
* Recall score (Healthy Loan): 0.99
* Presicion Score (High-risk Loan): 0.84
* Recall score (High-risk Loan): 0.99


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
both models predicted data almost similarly, model 1 provided a slightly accuracy while model 2 provided a better recall score. Theee best model to use would depend on what is more important, 
if accuracy is a must we would use model 1, if sensitivity is of most important, and detecting all values accurately, ten model 2 is better. 


* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
It is more important to determine the high-risk loans, since these are the ones that are the most volatiles for both the lender and the borrower alike. performance is important to accurately predict the outoutcome. 
