# credit-risk-classification
Module 20 Challenge - Supervised Learning.

Using various techniques to train and evaluate a model based on loan risk. A dataset of historical lending activity from a peer-to-peer lending services company is used to build a model that can identify the creditworthiness of borrowers.

## Credit Risk Analysis Report.
This report presents the development and evaluation of a logistics regression model run on loans that have been classified into two categories: healthy (label 0) and high risk (label 1). The objective was to create a model that accurately predicts the risk associated with each loan based on certain features.

# Data Preprocessing.
The dataset containing 77536 rows was read into a pandas DataFrame, this was split into y label from the loan_status column and the rest of the features into an X DataFrame. 

# Splitting the Data.
The data was then split into two subsets; a training set and a testing set. The training set was used to train the logistic regression model, this set contained the majority of the data at 58152 rows. The testing set was then used to evaluate the models performance.

# Logistics Regression Model.
A logistic regression model was chosen and trained on the target variables of loan classification labels, healthy loans labelled 0 and high-risk loans labelled 1.

# Model Evaluation.
After training the logistic regression model, its performance was evaluated using a confusion matrix and a classification report with precision, recall, F1-score, accuracy and weighted averages.

# Results.
The logistics regression model demonstrated the following perfomance metrics on the testing set:
* Precision:
    Label 0 (Healthy Loan): 1.00
    Label 1 (High-Risk Loan): 0.87
* Recall:
    Label 0 (Healthy Loan): 1.00
    Label 1 (High-Risk Loan): 0.95
* F1-Score:
    Label 0 (Healthy Loan): 1.00
    Label 1 (High-Risk Loan): 0.91
* Accuracy: 0.99

# Conclusion.
The logistics regression model performed very well in classifying loans in the healthy and high-risk categories. It achieved high precision and recall scores for both classes, with the high 80's of high-risk category the lowest score.
The testing dataset contained more loans classified as healthy so confidence can be very high this model will be able to predict healthy loans.


