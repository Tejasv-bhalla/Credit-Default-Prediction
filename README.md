# Credit Default Prediction

**Date**: June 2025  
**Author**: Tejasv Bhalla  
**Model Used**: XGBoost  
**F1-Score**: 86.72%  
**Final Accuracy**: 87.1%

## 📌 Overview

This project implements an end-to-end machine learning workflow for **credit default prediction** using real-world-like data from 25,000+ credit card customers. The aim is to assist financial institutions in identifying high-risk clients using advanced analytics, supporting both operational decision-making and strategic risk control.

> 📊 Our final model (XGBoost) achieved an F1-score of 0.8672 and an accuracy of 87.1%, balanced using a business-aligned classification threshold.

---

## 🔍 Problem Statement

To develop a machine learning model that predicts whether a customer will default on their credit card payment in the next month, based on demographic and financial behavior data.

---

## 🧠 Key Features

- Advanced **EDA** with demographic risk profiling
- Custom **feature engineering** (credit utilization, delinquency streak)
- **Data balancing** using SMOTE
- Hyperparameter tuning via **GridSearchCV**
- **Threshold optimization** using F1-score and Youden's J
- Business-aligned evaluation of false positives and false negatives
- Interpretable outputs via **SHAP** and feature importance

---

## 📂 Project Structure

```bash
credit-default-prediction/
│
├── data/                 # Contains train and validation datasets
├── notebooks/            # Main Jupyter notebook
├── outputs/              # Final prediction output
├── report/               # PDF report summarizing the full pipeline
├── requirements.txt      # Required libraries
├── README.md             # This file
└── .gitignore            # To ignore .ipynb_checkpoints etc.
