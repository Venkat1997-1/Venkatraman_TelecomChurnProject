Telecom Churn Prediction
Venkatraman
GDS09 Batch

Methods Used in Telecom Churn Prediction
Data Preprocessing

Handled missing values and outliers
Removed irrelevant features (e.g., mobile number, circle ID)
Converted float columns to integers for optimization
Exploratory Data Analysis (EDA)

Identified data imbalance (low churn rate)
Analyzed feature distributions and correlations
Feature Engineering

Selected 15 key features using Recursive Feature Elimination (RFE)
Addressed multicollinearity for better model stability
Handling Class Imbalance

Applied SMOTE (Synthetic Minority Over-sampling Technique)
Ensured balanced training data for better model generalization
Model Training & Evaluation

Logistic Regression (Baseline Model)
Accuracy: 82%, Recall for churners: 82%
Random Forest Classifier (Final Model)
Accuracy: 93%, Recall for churners: 69%
Business Insights & Interpretation

Identified key predictors of churn
Enabled data-driven customer retention strategies
