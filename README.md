# customer-churn-prediction-ml
End-to-end machine learning pipeline to predict customer churn and design a retention strategy. Handles severe class imbalance (1.9%) using Logistic Regression, SMOTE, and threshold tuning. Includes feature importance analysis and revenue-based business simulation.

📊 Customer Churn Prediction & Retention Strategy
🚀 Overview

Built an end-to-end machine learning pipeline to predict customer churn and evaluate retention strategies under severe class imbalance (1.9% churn rate).

📌 Problem

Predict churn customers and design a financially viable retention strategy.

🧠 Approach

Exploratory Data Analysis

Class imbalance handling (class weights + SMOTE)

Logistic Regression & Random Forest comparison

Threshold optimization

Risk ranking strategy

Revenue impact simulation

📈 Key Results

Achieved up to 74% recall on churn class

Identified tenure and behavioral features as strongest churn drivers

Demonstrated precision–recall tradeoff

Evaluated economic feasibility of retention campaigns

🛠 Tech Stack

Python

Pandas

Scikit-learn

Imbalanced-learn

Matplotlib / Seaborn

📂 Project Structure
churn_analysis.ipynb
universal_ml_training_dataset.csv
requirements.txt
💡 Business Insight

Mass targeting is not profitable. Risk-based ranking improves campaign efficiency.
