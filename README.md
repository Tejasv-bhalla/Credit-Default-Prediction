
# Credit Default Prediction 🚀

**Date:** June 2025  
**Author:** Tejasv Bhalla  
**Model:** XGBoost  
**F1‑score:** 86.72%  
**F2‑score:** 85.28%  
**Accuracy:** 87.10%

---

## 📌 Table of Contents
1. [Overview](#overview)
2. [Problem Statement](#problem-statement)
3. [Dataset & Features](#dataset--features)
4. [Project Workflow](#project-workflow)  
   4.1 [Exploratory Data Analysis](#41-exploratory-data-analysis)  
   4.2 [Feature Engineering & Preprocessing](#42-feature-engineering--preprocessing)  
   4.3 [Data Balancing](#43-data-balancing)  
   4.4 [Model Training & Tuning](#44-model-training--tuning)  
   4.5 [Threshold Optimization](#45-threshold-optimization)  
   4.6 [Evaluation & Interpretation](#46-evaluation--interpretation)  
5. [Usage](#usage)  
6. [Project Structure](#project-structure)  
7. [Results & Business Value](#results--business-value)  
8. [Future Enhancements](#future-enhancements)  
9. [Contact](#contact)

---

## Overview
Credit default prediction is critical for managing risk and enhancing decision-making in financial institutions. Using data from over 25,000 credit-card customers, this project builds an end-to-end machine learning pipeline—culminating in a robust XGBoost model achieving an F1‑score of **0.8672** and **87.1%** accuracy.

## Problem Statement
Predict whether a customer will default on their credit-card payment next month, using demographic and financial behaviour features. The focus is on high F1-score to balance recall and precision, aligning with real-world risk management priorities.

## Dataset & Features
- **Source:** 25,000+ credit‑card customers  
- **Key features:**
  - Demographics: age, education, marital status, gender
  - Financial: credit limit, payment history, bill amounts
  - Engineered: credit utilization ratios, delinquency streaks, repayment trends

## Project Workflow

### 4.1 Exploratory Data Analysis
- Demographic risk profiling
- Distribution analysis, outlier detection
- Visualization of feature correlations with default rates

### 4.2 Feature Engineering & Preprocessing
- Derived features: utilization and delinquency streaks
- Encoding of categorical features (one-hot, target encoding)
- Scaling numerical features

### 4.3 Data Balancing
- Applied SMOTE to address class imbalance

### 4.4 Model Training & Tuning
- Models evaluated: Logistic Regression, Random Forest, XGBoost
- Tuned hyperparameters using `GridSearchCV`

### 4.5 Threshold Optimization
- Selected thresholds via F1-score and Youden’s J statistic to align with business-defined trade-offs

### 4.6 Evaluation & Interpretation
- Metrics: Accuracy, Precision, Recall, F1-score
- Interpretability: SHAP values, feature importance visualizations

## Usage
```bash
git clone https://github.com/Tejasv‑bhalla/Credit‑Default‑Prediction.git
cd Credit‑Default‑Prediction
pip install -r requirements.txt

# Run notebook
jupyter notebook main.ipynb

# Or load pre-trained model and generate predictions
# ...
```

## Project Structure
```
├── train_dataset_final1.csv
├── validate_dataset_final.csv
├── final_predictions.csv
├── Report.pdf
├── main.ipynb
├── requirements.txt
└── README.md
```

## Results & Business Value
- **F1‑Score:** 0.8672  
- **F2‑Score:** 0.8528  
- **Accuracy:** 87.10%  
- False positives and negatives are evaluated based on financial costs, ensuring strategic alignment
- Fast‑installable pipeline for seamless deployment by financial risk teams

## Future Enhancements
- Integrate ensemble methods (e.g., stacking XGBoost, LightGBM, CatBoost)
- Deploy as REST API or dashboard
- Incorporate cost‑sensitive metrics and thresholds
- Experiment with deep learning (e.g., Tab‑Attention, CNN‑Transformer hybrids)

## 📬 Contact

Got suggestions or want to collaborate?

- GitHub: [@Tejasv-bhalla](https://github.com/Tejasv-bhalla)

---
