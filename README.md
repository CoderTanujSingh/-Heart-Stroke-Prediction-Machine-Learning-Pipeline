# 🫀 Heart-Stroke-Prediction (ML Pipeline Project)
### 📌 Project Title
### Heart Stroke Prediction Machine Learning Pipeline


📖 Project Overview

This project focuses on building an end-to-end Machine Learning pipeline to predict the likelihood of heart stroke based on patient clinical and lifestyle data.

The objective is to demonstrate:

Data preprocessing using ColumnTransformer

Handling missing values with proper imputation strategies

Ordinal & One-Hot Encoding

Feature Scaling

Feature Selection using Chi-Square

Model training using Decision Tree Classifier

Clean, production-ready ML Pipeline architecture

This project emphasizes building a modular, scalable, and interview-ready ML workflow.

📂 Dataset Description

The dataset contains patient health records including:

Demographic information (Gender, Age, Education)

Lifestyle indicators (Smoking habits)

Clinical measurements (Cholesterol, BP, BMI, Glucose)

Medical history (Diabetes, Hypertension, Stroke history)

Target Variable:

HeartStroke → Binary classification (Yes / No)

⚙️ ML Workflow
1️⃣ Data Cleaning

Standardized target labels

Converted target into binary format (0 / 1)

Handled missing values:

Median imputation for numerical features

Most frequent imputation for categorical features

2️⃣ Feature Engineering

Ordinal Encoding

Education level encoded based on natural hierarchy
Uneducated < Primary < Graduate < Postgraduate

One Hot Encoding

Gender

Previous Stroke History

Scaling

MinMax Scaling applied (required for Chi-Square feature selection)

3️⃣ Feature Selection

Applied SelectKBest using Chi-Square test

Selected top predictive features

4️⃣ Model Training

Algorithm Used: Decision Tree Classifier

Fully integrated inside sklearn Pipeline

Ensures no data leakage

🧠 Why This Project Matters

This project demonstrates:

Strong understanding of ML pipeline architecture

Clean preprocessing strategy using ColumnTransformer

Proper handling of categorical hierarchies

Feature selection using statistical methods

Reproducible modeling workflow

🛠 Tech Stack

Python

Pandas

NumPy

Scikit-Learn

Matplotlib / Seaborn

📊 Potential Improvements

Hyperparameter tuning (GridSearchCV)

Compare multiple models (Logistic Regression, Random Forest, XGBoost)

Cross-validation

ROC-AUC evaluation

SHAP for model explainability

🚀 Future Scope

This pipeline can be extended into:

Real-time health risk scoring API

Streamlit web application

Power BI dashboard for clinical analytics

Healthcare decision support system
