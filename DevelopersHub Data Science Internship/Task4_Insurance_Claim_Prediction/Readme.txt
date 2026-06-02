Task 4 — Predicting Insurance Claim Amounts
Field Details 
Objective Estimate medical insurance charges based on personal data 
Dataset Medical Cost Personal Dataset (Kaggle)
Model Linear Regression
MAE~$4,200R² Score~0.80

Approach:

Inspected dataset — no missing values found
Visualized charges distribution, smoker vs charges, age vs charges, BMI vs charges
Created correlation heatmap to identify strongest predictors
Encoded sex and smoker using .map(), region using One-Hot Encoding
Trained Linear Regression model
Evaluated using MAE, RMSE, and R² score

Key Insights:

Smoking status is the single strongest predictor of insurance charges
Smokers pay on average 3-4x more than non-smokers
Age and BMI both positively correlate with higher charges
Smokers with high BMI face the highest charges of all groups
Region has minimal impact on insurance costs
Model explains approximately 80% of variation in insurance charges

Skills Demonstrated:

Regression modeling using Linear Regression
Feature correlation analysis and heatmap visualization
Error evaluation using MAE and RMSE
R² score interpretation

