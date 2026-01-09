📊 Employee Salary Prediction using Linear Regression
📌 Project Overview

This project aims to predict employee salary (LPA) using Linear Regression based on multiple factors such as experience, education level, skill score, and certifications.
Both Simple Linear Regression and Multiple Linear Regression models are built and compared to understand the impact of additional features on prediction accuracy.

🎯 Problem Statement

Salary is influenced by multiple factors, not just years of experience.
The objective of this project is to:

Predict employee salary using regression techniques

Compare Simple vs Multiple Linear Regression

Interpret feature impact on salary

Draw meaningful business insights

📂 Dataset Description

The dataset contains the following columns:

Column Name	Description
Experience_Years	Total years of work experience
Education_Level	Education level (1 = UG, 2 = PG, 3 = PhD)
Skill_Score	Skill rating (0–100)
Certifications	Number of certifications
Salary_LPA	Salary in Lakhs per Annum (Target Variable)

The dataset intentionally contains real-world noise, making predictions realistic rather than perfect.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

🔍 Project Workflow
1️⃣ Data Exploration (EDA)

Checked data types and missing values

Generated summary statistics

Visualized relationships using scatter plots and correlation analysis

2️⃣ Data Preparation

Selected relevant features and target variable

Split data into training and testing sets (80/20 split)

3️⃣ Model Building

Simple Linear Regression using only Experience_Years

Multiple Linear Regression using all features

4️⃣ Model Evaluation

Models were evaluated using:

R² Score

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

5️⃣ Visualization

Actual vs Predicted plot

Regression line (Simple LR)

Residual analysis

📈 Model Performance Comparison
Model	R²	MAE	RMSE
Simple Linear Regression	0.97	0.38	0.54
Multiple Linear Regression	0.99	0.32	0.35

✅ Multiple Linear Regression performs better, indicating salary is influenced by multiple factors.

📌 Feature Importance (Multiple Linear Regression)
Feature	Impact
Experience_Years	Strong positive impact
Certifications	Significant positive impact
Skill_Score	Moderate positive impact
Education_Level	Negative coefficient due to categorical encoding

Note: Education_Level is a categorical feature encoded numerically. One-hot encoding would improve interpretability.

💡 Key Insights

Experience is the strongest predictor of salary

Certifications and skill score significantly increase salary

Salary prediction improves when multiple features are considered

Linear Regression is suitable for this problem with realistic data noise

⚠️ Limitations

Dataset is synthetic and limited in size

Education level treated as numeric instead of categorical

Real-world factors like company, role, and location are not included

🚀 Future Improvements

Apply One-Hot Encoding for categorical variables

Try Polynomial Regression

Implement Ridge and Lasso Regression

Use cross-validation for better generalization

📌 Conclusion

This project demonstrates an end-to-end implementation of Linear Regression, including data analysis, model building, evaluation, and interpretation. It highlights the importance of using multiple features to improve predictive accuracy and reflects a realistic business scenario.

🧠 Author

Franco A
Senior Engineer | Data Analytics & Machine Learning Enthusiast