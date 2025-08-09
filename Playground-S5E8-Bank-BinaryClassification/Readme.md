# 🏦 Bank Binary Classification – Kaggle Project  

[![View on Kaggle](https://img.shields.io/badge/View%20on-Kaggle-20BEFF?logo=kaggle)](https://www.kaggle.com/code/hamidrana/bank-binary-classification)  
🔗 [Kaggle Notebook Link](https://www.kaggle.com/code/hamidrana/bank-binary-classification)  

---

## 📌 Project Overview
The goal of this project is to build a **machine learning model** that predicts whether a bank client will **subscribe to a term deposit** based on demographic, financial, and campaign-related features.

### 🎯 Objective:
- Predict the binary target `y` (**Yes** or **No**).
- **Evaluation Metric:** ROC AUC Score (used in competition settings).
- Focus on achieving a **high ROC AUC** rather than just accuracy.

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- LightGBM, XGBoost, CatBoost  
- Matplotlib, Seaborn (EDA)  

---

## 🚀 My Approach
1. **Data Preprocessing:**
   - Encoded categorical variables.
   - Handled missing values and ensured consistent data types.
   - Balanced the dataset for better training.

2. **Model Exploration:**
   - Tested **LightGBM**, **XGBoost**, and **CatBoost**.
   - Compared metrics on validation sets.

3. **Hyperparameter Tuning:**
   - Used **RandomizedSearchCV** for faster optimization.
   - Tuned for maximum ROC AUC.

4. **Results:**
   - **LightGBM:** 0.9178  
   - **XGBoost:** 0.9201  
   - **CatBoost:** **0.9239** (best performing model before tuning)

---

## 🔥 Final Outcome
| Model     | ROC AUC Score |
|-----------|---------------|
| LightGBM  | 0.9178        |
| XGBoost   | 0.9201        |
| CatBoost  | **0.9239**    |

---

## 🤝 Collaboration Invitation
This project is **open for contributions**!  
If you have ideas for improving the ROC AUC score—whether through better **feature engineering**, **ensemble models**, or **tuning**—feel free to fork the notebook and experiment.

---

## 📎 Notebook Link  
🔗 [View My Kaggle Notebook](https://www.kaggle.com/code/hamidrana/bank-binary-classification)  

---

## 🙋‍♂️ About Me  
🔗 [**My Kaggle Profile**](https://www.kaggle.com/hamidrana)  

