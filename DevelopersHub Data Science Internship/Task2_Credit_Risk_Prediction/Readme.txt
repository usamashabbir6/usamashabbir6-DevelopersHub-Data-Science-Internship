Task 2 — Credit Risk Prediction
Field Details
Objective Predict whether a loan applicant will default on a loan
DatasetLoan Prediction Dataset (Kaggle)
Model Logistic Regression
Accuracy~78.86%

Approach:

Handled missing values using mode (categorical) and median (numerical)
Visualized loan status distribution, education vs loan status, and income vs loan amount
Encoded categorical features using .map() and pd.get_dummies()
Trained Logistic Regression classifier
Evaluated using accuracy score and confusion matrix

Key Insights:

Graduates have significantly higher loan approval rates than non-graduates
Credit history is the strongest predictor of loan approval
Most loan amounts fall between 100,000 and 200,000
Model performs better at predicting approvals than rejections

Skills Demonstrated:

Data cleaning and handling missing values
Exploratory Data Analysis (EDA)
Binary classification using Logistic Regression
Model evaluation using confusion matrix and accuracy