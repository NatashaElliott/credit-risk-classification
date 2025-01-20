# Module 20

## Overview of the Analysis: Explain the purpose of this analysis.

The purpose of this analysis was to determine if the Logistic Regression model is appropriate for predicting the creditworthiness of borrowers from a peer-to-peer lending service company. The model was based on historical lending activity.

The first stage of preparing the data was to take the original dataset consisting of information based on 77536 loans, with the loan status being the subject of the prediction. The remaining information about the loan is included in the following columns:

- Loan size
- Interest rate
- Borrower income
- Debt to income
- Number of accounts
- Derogatory marks against the Borrower
- Total debt

This dataset was used to train a Linear Regression model which was then used to predict if the loan status was healthy (0) or high risk (1). 

## Results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

- Accuracy: 0.99

Label 0:
- Precision: 1.00
- Recall: 0.99

Label 1:
- Precision: 0.85
- Recall: 0.91

## Summary: Summarise the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
The Logistic Regression model is extremely accurate, has high precision, and high recall which indiciates that the model is more than sufficient for predicting the behaviour of borrowers engaging in peer-to-peer lending. From a business perspective, I would recommend using this model as it would reduce risk due to its accuracy in predicting future behaviour based on past lending activity. 

# Credits
All code written by Natasha Elliott.
