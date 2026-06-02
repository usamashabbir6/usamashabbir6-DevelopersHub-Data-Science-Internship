Task 5 — Personal Loan Acceptance Prediction
Field Details
Objective Predict which customers are likely to accept a personal loan offer
Dataset Bank Marketing Dataset (Kaggle)
Model Decision Tree Classifier
Accuracy~88-90%

Approach:

Performed EDA on age, job, marital status, and campaign contacts
Encoded all categorical columns using LabelEncoder in a loop
Used stratify=y during train-test split to handle class imbalance
Trained Decision Tree Classifier with max_depth=5
Visualized the decision tree structure
Extracted business insights by analyzing acceptance rates per customer group

Key Insights:

Only ~11% of customers accepted the loan offer — heavily imbalanced dataset
Call duration is the strongest predictor — longer calls signal genuine interest
Students and retired customers have the highest acceptance rates
Single customers are slightly more likely to accept than married ones
Over-contacting customers during a campaign reduces acceptance likelihood
Tertiary education customers show higher acceptance rates

Business Recommendation:

Focus marketing on students, retired customers, and those with tertiary education
Limit contact attempts per customer to avoid fatigue and rejection
Prioritize longer, quality conversations over repeated short contacts

Skills Demonstrated:

Data exploration and visualization
Decision Tree classification modeling
Business insight extraction from model results
Handling imbalanced datasets using stratified splitting