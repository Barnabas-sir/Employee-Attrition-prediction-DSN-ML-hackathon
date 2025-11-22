# Employee Attrition prediction-DSN-ML-hackathon
This project focuses on predicting employee attrition using machine learning techniques. The goal is to generate probability scores for each employee in the test set, evaluated using AUC (ROC curve) as the primary metric.
Built an employee attrition prediction model using a clean ML pipeline with One-Hot Encoding and Stratified K-Fold.

Tested Logistic Regression, Random Forest, and XGBoost baselines.

Tuned both Random Forest and XGBoost using RandomizedSearchCV.

XGBoost achieved the highest cross-validated AUC (0.8282).

Final tuned XGBoost model was trained on full data and used to generate probability-based attrition predictions for submission.
