# Chocolate-Sales-Analysis-Prediction
A machine learning project to analyze and predict chocolate sales, using Random Forest Regressor for sales prediction and Logistic Regression for classification. Includes data preprocessing, feature engineering, exploratory analysis, and model evaluation.

Key Features:
✅ Data Preprocessing:

Handling missing data by imputing numerical columns with the median and categorical columns with the most frequent value.
Removing duplicates to ensure a clean dataset.
Scaling numerical features for uniformity using StandardScaler.
Encoding categorical features into numerical values using LabelEncoder.
✅ Feature Engineering:

Revenue Calculation: Computes the total revenue by multiplying Quantity and Price.
Total Value Feature: Adds a new feature by summing Quantity and Price.
Chi-Square Test: Evaluates associations between categorical features like Product Type and Region.
✅ Exploratory Data Analysis (EDA):

Correlation Matrix: Analyzes the relationship between numerical variables.
Frequency Counts & Mode: Summarizes categorical variables.
✅ Predictive Modeling:

Random Forest Regressor: Predicts continuous sales values based on features.
Logistic Regression: Classifies sales as either high or low (binary classification).
✅ Model Evaluation:

Regression Metrics: Measured using Mean Squared Error (MSE) and R-squared (R²).
Classification Metrics: Evaluated using Accuracy and Confusion Matrix for binary sales classification.
