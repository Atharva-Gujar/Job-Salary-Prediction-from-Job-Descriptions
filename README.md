# Job-Salary-Prediction-from-Job-Descriptions
The "Job Salary Prediction from Job Descriptions" project involves using machine learning to predict job salaries based on job descriptions. By analyzing text data such as job title, skills required, experience, and location, the model predicts a salary range, helping both job seekers and employers gauge compensation expectations.

Data Collection

Job title, description, location, years of experience, required skills, benefits, and actual salary

Data Preprocessing

Clean text (job descriptions), normalize casing, remove HTML, stopwords

Handle missing values, encode categorical data (industry, location)

Feature Engineering

NLP Features: TF-IDF on job description

Create new features: seniority level, role type (engineer, manager), city avg salary, etc.

Modeling

Try Linear Regression first

Then apply Ridge, Lasso, ElasticNet

Compare with Random Forest or XGBoost Regressor

Evaluation

Use RMSE, MAE, R² to compare performance

Residual plots, salary range predictions

Presentation

Build visual dashboard with salary ranges by role & city

Export top 10 most valuable skills per role
