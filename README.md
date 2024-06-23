# Credit-Risk-Classification
Challenge 20
# Overview
- The goal of this analysis is to create and assess a logistic regression model that predicts applicants' loan statuses using past lending data. This model is intended to assist the company in making informed decisions on loan approvals or denials based on applicant characteristics.
# Accuracy, Precision, and Recall Scores
- Accuracy: The overall accuracy of the model is 99%.
- Precision for class 0 (loan not defaulted): 1.00
- Precision for class 1 (loan defaulted): 0.85
- Recall for class 0: 0.99
- Recall for class 1: 0.91
# Summary of Results
- Accuracy: The model obtained an accuracy of 99%, indicating that it correctly predicted the loan status of 99% of the cases in the test set.
- Precision and Recall: For non-defaulted loans (class 0), the model has a perfect precision score of 1.00, implying that all predicted non-defaults were actual non-defaults. The recall score of 0.99 indicates that 99% of actual non-defaults were correctly identified by the model. For defaulted loans (class 1), the model achieved a precision score of 0.85, indicating that 85% of loans predicted as defaults were actual defaults. The recall score of 0.91 shows that 91% of actual defaults were correctly identified.
# Recommendation
- Based on the evaluation metrics, I recommend using this logistic regression model for predicting loan statuses for the following reason:
  - High Accuracy: 99% accuracy indicates that the model is reliable with predicting the loan outcomes.
  - Precision and Recall (class 1): Although the relatively low precision score for defaulted loans, the recall score of 0.91 ensures that the model effectively identifies most defaults.
  - Precision and Recall (class 0): The model has high precision and recall for non-defaulted loans guarantees and minimizes the risk of false positives.
- Based on the above justification, the model is a robust and effective tool for loan approvals, providing good balance between risk management and operational efficiency. 
