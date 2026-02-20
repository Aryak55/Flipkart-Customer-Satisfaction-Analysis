Flipkart Customer Satisfaction Analysis & Prediction
🔷 Project Overview

This project analyzes customer support data to understand key drivers of customer satisfaction (CSAT) and builds predictive machine learning models to identify dissatisfied customers proactively.

The analysis follows a structured approach including:

Exploratory Data Analysis (EDA)

Hypothesis Testing

Feature Engineering & Data Preprocessing

Handling Imbalanced Dataset

Machine Learning Model Implementation

Hyperparameter Optimization

Model Evaluation & Business Impact Analysis

🔷 Dataset Description

The dataset contains ~85,000+ customer support interaction records including:

Service channel information

Issue categories and sub-categories

Resolution time

Handling time

Agent tenure & shift details

Product category & item price

Customer satisfaction (CSAT Score)

Target Variable:

CSAT_Class (Binary Classification: Satisfied / Dissatisfied)

🔷 Business Objective

To identify dissatisfied customers early and understand operational factors affecting satisfaction, enabling proactive customer retention strategies and service optimization.

🔷 Key Insights from EDA

Resolution Time has a strong negative relationship with customer satisfaction.

Service Channel significantly impacts CSAT.

Operational efficiency variables are more influential than pricing.

Certain issue categories consistently show lower satisfaction.

🔷 Hypothesis Testing

Statistical tests confirmed:

Resolution time significantly affects satisfaction (T-test).

Service channel and satisfaction are statistically associated (Chi-square test).

🔷 Handling Imbalanced Dataset

The dataset was imbalanced with a higher proportion of satisfied customers.

Class weighting was applied in machine learning models to improve minority class detection (dissatisfied customers).

🔷 Machine Learning Models Implemented

1️⃣ Logistic Regression (Balanced)
2️⃣ Random Forest (Balanced)

Evaluation Metrics Used:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Recall for dissatisfied customers was prioritized due to its direct business impact.

🔷 Final Model Selection

Balanced Logistic Regression was selected as the final model because:

Higher recall for dissatisfied customers

Better minority class detection

Strong alignment with business objectives

🔷 Feature Importance

Most influential features:

Resolution_Time_Minutes

connected_handling_time

channel_name

category

Product_category

Operational efficiency emerged as the strongest driver of customer satisfaction.

🔷 Business Impact

The final model enables:

Early detection of dissatisfied customers

Proactive customer retention

Channel optimization

Service process improvement

Data-driven operational decision-making

🔷 Technologies Used

Python

Pandas

NumPy

Seaborn & Matplotlib

Scikit-learn

GridSearchCV

Google Colab
