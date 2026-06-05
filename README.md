# Employee Attrition Prediction using Machine Learning
## Project Overview
Employee attrition is a major challenge for organizations because replacing employees involves recruitment costs, training expenses, and productivity loss. This project aims to predict whether an employee is likely to leave the organization based on various demographic, professional, and workplace-related factors.
Using Machine Learning techniques, the project analyzes employee data and builds predictive models that help HR departments identify employees at risk of attrition and take proactive retention measures.

## Objectives
i. Analyze employee attrition patterns.
ii. Identify key factors influencing employee turnover.
iii. Build classification models to predict attrition.
iv. Compare multiple machine learning algorithms.
v. Apply cross-validation for reliable model evaluation.
vi. Perform hyperparameter tuning to improve model performance.
vii. Generate business insights using feature importance analysis.

## Dataset Information
The dataset contains information about employees, including:
i. Employee ID
ii. Age
iii. Gender
iv. Department
v. Job Role
vi. Monthly Income
vii. Education Level
viii. Work Experience
ix. Overtime Status
x. Job Satisfaction
xi. Work-Life Balance

## Target Variable
i. Yes → Employee likely to leave
ii. No → Employee likely to stay

## Technologies Used
i. Python
ii. Pandas
iii. NumPy
iv. Matplotlib
v. Seaborn
vi. Scikit-Learn

## Machine Learning Workflow
### 1. Data Loading
The dataset was loaded using Pandas and inspected to understand its structure, data types, and feature distribution.
### 2. Data Exploration
Exploratory Data Analysis (EDA) was performed to understand employee behavior and attrition trends.
### 3. Data Preprocessing
i. Removed irrelevant features such as Employee ID.
ii. Encoded categorical variables using One-Hot Encoding.
iii. Standardized numerical features using StandardScaler.
iv. Split data into training and testing sets.
### 4. Model Building
The following classification models were implemented:
i. Logistic Regression : Used as a baseline classification model.
ii. Random Forest Classifier : Used as the primary model due to its robustness and ability to capture complex relationships.
### 5. Model Evaluation
The models were evaluated using:
i. Accuracy Score
ii. Confusion Matrix
iii. Precision
iv. Recall
v. F1-Score
vi. Classification Report
### 6. Cross Validation
5-Fold Cross Validation was applied to obtain a more reliable estimate of model performance and reduce dependency on a single train-test split.
### 7. Hyperparameter Tuning
GridSearchCV was used to identify the optimal Random Forest parameters, including:
i. Number of Trees (n_estimators)
ii. Maximum Tree Depth (max_depth)
iii. Minimum Samples Split (min_samples_split)
## 8. Feature Importance Analysis
Random Forest feature importance scores were used to identify the factors contributing most to employee attrition.

## Visualizations Included
i. Attrition Distribution

<img width="580" height="453" alt="image" src="https://github.com/user-attachments/assets/2331ec21-7795-424d-ad00-7a75cbe2b2d1" />

ii. Department-wise Attrition

<img width="859" height="493" alt="image" src="https://github.com/user-attachments/assets/cec9c0aa-56cc-49bf-ad50-9316a03beaf7" />

iii. Overtime vs Attrition

<img width="580" height="432" alt="image" src="https://github.com/user-attachments/assets/bd7936b1-8d89-45da-bd32-1148cd1a6913" />

iv. Monthly Income vs Attrition

<img width="713" height="448" alt="image" src="https://github.com/user-attachments/assets/c0f24354-ad8e-476b-a5f2-163bd35e5129" />

v. Correlation Heatmap

<img width="1326" height="1043" alt="image" src="https://github.com/user-attachments/assets/ea07b5a2-3114-4b03-88e6-949322913888" />

## Results
The Random Forest model outperformed the baseline Logistic Regression model and provided better predictive performance.

## Conclusion
This project demonstrates the complete machine learning pipeline for solving a real-world HR Analytics problem. Through data preprocessing, exploratory analysis, model training, cross-validation, hyperparameter tuning, and feature importance analysis, the project successfully predicts employee attrition and provides actionable business insights for employee retention.
