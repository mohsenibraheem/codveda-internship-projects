# Predictive Modelling (Classification)
I built an ML model to predict customer's churn using Logistic Regression, Decision Tree and Random Forest Modelss.

The Dataset that was trained to this model contained some columns like State, Account length, Area code, Total day minutes, Total day calls, Total intl calls, Total night calls, Churn and much more.

## Models Used
They Models that were used in this project are;

 - Logistic Regression:

   This model is was built to calculate probability of something happening.
 - Decision Tree:

   Decision Tree like a flowchart, it asks a questions series of question to reach a final conclusion.
 - Ranadom Forest:

   This Model builds many decision trees (Forest) and averages their results.

## Result
After preprocessing the customer churn dataset, three classification models were trained and evaluated.
- Logistic Regression
- Decision Tree
- Random Forest

### The Models were evaluated using;
- Accuracy 
- Precison
- Recall
- F1-Score

Initial evaluation showed High Accuracy but Low recall and F1-Score.

This indicate that the dataset was imbalanced, as the models were better at predicting non-churn customers than churn customers.

## Conclusion
This project successfully demonstrates how machine learning classification algorthms can be used to predict customer churn

The dataset was preprocessed through:
- Handling
- Feature Scalling
- Train-test-split

Among all models Random Forest ahieved the best overall performance after tuning, making it the most suitable model for churn prediction in this project.

This project highlights the importance of:
- Proper preprocessing
- Model Evaluation
- Handling Imbalanced dataset
- Hyperparamter Tuning