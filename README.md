# bank-loan-approval-rf-gb
Bank Loan Prediction Using Random Forest and Gradient Boosting
📌 Project Objective
Build a machine learning model to predict whether a loan application will be approved based on applicant information. This helps financial institutions automate and improve decision-making.

Dataset
Source: Bank loan dataset containing information on applicants like gender, marital status, income, credit history, etc.

Target: Loan_Status (Y/N) — whether the loan was approved or not.

🔧 Steps Performed

1.Data Cleaning:
  * Handled missing values in features like Gender, Married, Self_Employed, etc.
  * Dropped unnecessary columns (Loan_ID).

2.Exploratory Data Analysis (EDA) (To be expanded visually):
  * Used .describe() and .value_counts() to understand the data.
  * Explored correlations and potential predictive variables.

3.Feature Engineering:
  * Converted categorical variables into numerical using label encoding/dummies.
  * Ensured balanced class distribution and no data leakage.

4.Modeling:
  * Applied Random Forest Classifier
  * Applied XG Boosting Classifier
  * Evaluated using Accuracy, Confusion Matrix, and Classification Report.

5.Model Comparison:
  * Compared performance of both models to determine which works better on this dataset.

📈 Conclusion
Both models performed well on unseen data.
🔹 XGBoost slightly outperformed Random Forest on training data and matched its test accuracy — making it the preferred model for deployment.
🔹 Random Forest remains a strong baseline due to its speed and simplicity.
