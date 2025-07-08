# 📊 XGBoost-Based Academic & Health Data Predictor

This repository contains an XGBoost model trained to analyze **academic performance** and **health data** for early prediction of mental health risks. It is developed as part of the **AI Powered Smart Cognitive Tracker** — a multimodal AI system designed to identify cognitive and emotional decline in adolescents.

---

## 🎯 Project Context

Changes in grades, attendance, or health symptoms often reflect early mental distress. This model uses structured tabular data (e.g., marks, BMI, absenteeism) to detect patterns that correlate with emotional or cognitive decline.

---

## 🧠 Model Details

| Component       | Description                                  |
|----------------|----------------------------------------------|
| Model           | XGBoost (Gradient Boosting Trees)            |
| Task            | Binary/Multiclass mental health classification |
| Data Type       | Structured CSV or Excel datasets             |
| Framework       | scikit-learn + xgboost                       |
| Platform        | Google Colab                                 |
| Project Context | Part of AI Powered Smart Cognitive Tracker   |

---

## 📂 Files Included

- `XGBoost MODEL TRAINING.ipynb`  
  → Colab notebook with preprocessing, feature engineering, training, and evaluation.

- `data/`  
  → Sample academic/health dataset used in training (CSV or XLSX)

---

## 🚀 Run on Google Colab

Click below to open and run in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Suroochi3/xgboost-mental-health-predictor/blob/main/XGBoost%20MODEL%20TRAINING.ipynb)

---

## 📦 Requirements

```bash
pip install xgboost
pip install pandas scikit-learn matplotlib seaborn
