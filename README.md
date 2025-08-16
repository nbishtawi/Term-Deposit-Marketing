# Term Deposit Marketing Prediction  

## Overview  
**Term Deposit Marketing Prediction** is a machine learning project that predicts whether a customer will subscribe to a term deposit based on demographic, financial, and campaign-related features.  
The project applies classification models, class imbalance techniques, and interpretability methods to support marketing decision-making.  

This project was originally developed in a notebook called *Assignment 2 Final Workbook.ipynb* and has now been renamed and documented for clarity and reproducibility.  

Note: The dataset (term-deposit-marketing-2020.csv) is **not included** in this repository due to proprietary restrictions.  

---

## Goals  
- Predict if a customer will **subscribe (yes/no)** to a term deposit.  
- Identify which demographic, financial, and campaign factors most influence customer decisions.  
- Build interpretable models to assist marketing campaign strategies.  

---

# Methodology  
1. **Data Preparation** – Imported marketing campaign data, handled missing values, scaled/encoded features.  
2. **Exploratory Analysis** – Investigated feature distributions and correlations with term deposit subscription.  
3. **Model Training** – Trained multiple classifiers to predict customer subscription.  
4. **Model Tuning** – Hyperparameter optimization via cross-validation.  
5. **Interpretability** – SHAP and LIME used to understand feature impact.  

---

## Results  
- Ensemble models (Random Forest, XGBoost, Gradient Boosting) outperformed single classifiers.  
- Key features influencing subscription included **contact duration**, **campaign frequency**, and **customer balance**.  
- SHAP and LIME confirmed that campaign-related features played the strongest role in customer decisions.  

---

## Tools & Technologies  
- **Python**  
- **Scikit-learn** – preprocessing, models, evaluation  
- **XGBoost** – boosting methods  
- **Imbalanced-learn** – SMOTE/undersampling  
- **LIME, SHAP** – interpretability  
- **Matplotlib, Seaborn** – visualization  
- **Pandas, NumPy** – data handling  
