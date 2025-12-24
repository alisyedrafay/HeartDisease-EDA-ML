# Heart Disease Prediction Project

## Overview
This project predicts the likelihood of heart disease in patients using machine learning. The dataset is preprocessed, analyzed, and modeled using Python, Pandas, Seaborn, and scikit-learn. The project demonstrates feature encoding, visualization, and ML model evaluation.

---

## Features
- Data cleaning and preprocessing
- Handling categorical variables:
  - One-Hot Encoding for nominal features (e.g., Sex)
  - Ordinal Encoding for ordered features (e.g., ChestPainType)
- Exploratory Data Analysis (EDA) with visualizations
- Outlier detection and removal
- Train-Test split for model validation
- Implementation of ML models for classification
- Evaluation using accuracy, confusion matrix, and classification report

---

## Dataset
- Source: [Provide dataset link if any, e.g., Kaggle Heart Disease Dataset]
- Features include Age, Sex, ChestPainType, Cholesterol, MaxHR, etc.
- Target variable: `HeartDisease` (1 = presence, 0 = absence)

---

## Preprocessing
- Categorical features are encoded using One-Hot and Ordinal Encoding
- Outliers detected via IQR and visualized using boxplots
- Numerical features scaled if required
- Missing values handled appropriately

---

## Models Implemented
- Logistic Regression
- Decision Trees / Random Forest
- (Optional: SVM, XGBoost)

---

## How to Run
1. Clone this repository:
   ```bash
   git clone <repo-url>
   cd <repo-folder>

