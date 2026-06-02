Task 3 — Customer Churn Prediction (Bank Customers)
Field Details
Objective Identify customers who are likely to leave the bank
Dataset Churn Modelling Dataset (Kaggle)
Model Logistic Regression
Accuracy~81.26%

Approach:

Dropped non-predictive columns: RowNumber, CustomerId, Surname
Encoded Gender using Label Encoding and Geography using One-Hot Encoding
Applied StandardScaler to normalize features before training
Trained Logistic Regression classifier
Analyzed feature importance using model coefficients

Key Insights:

Dataset has approximately 20% churn rate — imbalanced dataset
Older customers churn significantly more than younger ones
Germany has the highest churn rate among France, Spain, and Germany
Customers with 3-4 products surprisingly show very high churn rates
Being an active member strongly reduces the probability of churning
Age and Geography (Germany) are the top churn predictors

Skills Demonstrated:

Categorical data encoding (Label Encoding and One-Hot Encoding)
Feature scaling using StandardScaler
Supervised classification modeling
Feature importance interpretation using model coefficients