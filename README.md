# Employee_Promotion_Prediction
## Problem
In organizations, identifying the right employees for promotion is crucial for biased promotion decisions, maintaining motivation, and retaining talent. This project aims to build a machine learning model to predict whether an employee is likely to be promoted, based on historical data and performance indicators, to support data-driven and fair HR decision-making.
## Dataset Information
- employee_id: Unique ID for employee
- department: Department of employee
- region: Region of employment
- education: Education Level
- gender: Gender of Employee
- recruitment_channel: Channel of recruitment for employee
- no_ of_ trainings: no of other trainings completed in previous year on soft skills, technical skills etc.
- age: Age of Employee
- previous_ year_ rating: Employee Rating for the previous year
- length_ of_ service: Length of service in years
- awards_ won?: if awards won during previous year then 1 else 0
- avg_ training_ score: Average score in current training evaluations
- is_promoted: (Target) Recommended for promotion
## Approach Used
- Handled missing values, encoded categorical features, and addressed class imbalance using SMOTE.
- Performed Exploratory Data Analysis (EDA) to understand relations between features and distributions of features.
- Trained and compared several models including Logistic Regression, Decision Tree, Random Forest, and XGBoost. Optimized model performance using Grid Search and Cross-Validation.
- Used accuracy, precision, recall, F1-score, and AUC-ROC, with a focus on recall to reduce false negatives (i.e., missing a promotable employee).
## Impact
- Helps organizations make informed promotion decisions based on data, improving fairness and transparency.
- Helps organizations retain top performers by recognizing and rewarding merit.
