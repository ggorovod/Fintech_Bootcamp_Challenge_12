# Module 12 Report 

## Overview of the Analysis

Credit risk classification analysis using imbalanced_learn library techniques. Logistic Regression Model comparison and analysis between original provided data and oversampled data. The purpose of this exercise is to create a machine learning model that identifies risky loans in a pool of data that contains mostly healthy (less risky) loans.

* The purpose of this exercise is to create a machine learning model that identifies risky loans in a pool of data that contains mostly healthy (less risky) loans.
* Data (csv file) used for the exercise contained a list of over 77,000 loans with a collection of relevant features such as the customers' income, debt-to-income ratio,  loan size, and loan status(default or no default)
* The model attempts to predict high-risk loans from a large pool of loans that are mostly not high-risk. The generated model then was evaluated for accuracy, precision, recall, etc. 
* The machine learning stages included:
  - Importing data into an IDE and spliting it into test and train sets
  - Selecting a machine learing model for the provided data (Logistic Regression with Oversampling techniques)
  - Fitting the model to the data (using .fit function)
  - Prediting the results of the ML model (using .predict funtion)
  - Evaluating the model predicition result and ability to select high risk loans based on the provided features. 
* The exercised employed LogisticRegression Model methods and RandomOversampler to compensate for the much smaller high-risk loan class in the data set. This allowed for a higher overall reliablity to be generated with the model. 

## Results

* Machine Learning Model 1 (orignial):
  - Accuracy: 95.4%
  - Precision for high-risk loans: 85%
  - Recall for high-risk loans: 91%



* Machine Learning Model 2 (using oversampling):
  - Accuracy: 99.5%
  - Precision for high-risk loans: 85%
  - Recall for high-risk loans: 100%


## Summary

For this particular dataset, the oversampling techniques generated a higher level or accuracy and recall of 100% without sacrificing precision which stayed at 85% (same as  original data). The results of this exercise clearly show that using Oversampling will generate a more reliable model for identifiying high-risk loans. 

The data supports a recommindation for Oversampled LinearRegression ML Model over original sample data.
