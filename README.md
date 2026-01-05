📊 Term Deposit Subscription Prediction (Bank Marketing)
📌 Project Overview

This project builds a machine learning classification model to predict whether a bank customer will subscribe to a term deposit after a marketing campaign. The solution uses the Bank Marketing Dataset from the UCI Machine Learning Repository and applies Explainable AI (SHAP) to interpret model predictions.

The goal is to help banks optimize marketing strategies, reduce campaign costs, and improve customer targeting using data-driven insights.

🎯 Problem Statement

Banks conduct large-scale marketing campaigns to promote term deposits, but contacting every customer is inefficient and expensive. The challenge is to identify customers who are most likely to subscribe, based on demographic, financial, and campaign-related data.

✅ Objectives

Load and analyze a real-world online banking dataset

Preprocess and encode categorical features

Train a Random Forest classification model

Evaluate performance using Confusion Matrix, F1-Score, and ROC-AUC

Apply SHAP for global and local model interpretability

📂 Dataset

Source: UCI Machine Learning Repository

Dataset: Bank Marketing (bank-additional-full.csv)

Records: 41,188

Features: 20 input features

Target Variable:

y = 1 → Customer subscribed to term deposit

y = 0 → Customer did not subscribe

The dataset is loaded directly from the online source within the program.

🛠️ Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib

SHAP (Explainable AI)

⚙️ Methodology

Data Loading: Dataset downloaded programmatically from UCI repository

Preprocessing:

One-Hot Encoding for categorical features

Train–test split with stratification

Model Training: Random Forest Classifier

Evaluation Metrics:

Confusion Matrix

F1-Score

ROC-AUC and ROC Curve

Explainability:

SHAP Summary Plot (global importance)

SHAP Waterfall Plots (individual predictions)

📈 Results

The Random Forest model achieved strong predictive performance

Key features such as call duration, campaign interactions, and economic indicators significantly influenced predictions

SHAP explanations improved transparency and trust in model decisions
