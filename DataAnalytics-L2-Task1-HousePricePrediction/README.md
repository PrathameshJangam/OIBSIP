# 🏠 House Price Prediction using Linear Regression

## 📌 Overview

This project predicts house prices using **Linear Regression** on the **Ames Housing Dataset**. It covers the complete machine learning workflow from data preprocessing and EDA to model evaluation and interpretation.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Handle missing values
- Encode categorical features using One-Hot Encoding
- Select relevant features
- Analyze feature correlations
- Train a Linear Regression model
- Evaluate using MSE, RMSE, and R²
- Analyze residuals and model coefficients
- Compare Linear Regression with Ridge Regression

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Dataset

**Ames Housing Dataset** from Kaggle.


Dataset: [https://www.kaggle.com/datasets/prevek18/ames-housing-dataset](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)

---

## 🔍 Features Used

- `Gr Liv Area`
- `Overall Qual`
- `Year Built`
- `Total Bsmt SF`
- `Garage Cars`
- `Full Bath`
- `Bedroom AbvGr`
- `Neighborhood`

---

## ⚙️ Workflow

Data Loading
→ EDA
→ Feature Selection
→ Missing Value Handling
→ One-Hot Encoding
→ Correlation Analysis
→ Train/Test Split (80/20)
→ Linear Regression
→ Evaluation
→ Residual & Coefficient Analysis
→ Ridge Regression Comparison

---

## 📈 Results

| Model | MSE | RMSE | R² |
|---|---:|---:|---:|
| **Linear Regression** | **1.293 × 10⁹** | **35,961.52** | **0.8387** |
| Ridge Regression | 1.553 × 10⁹ | 39,410.48 | 0.8063 |

**Linear Regression performed better than Ridge Regression** based on MSE, RMSE, and R².

---

## 🏆 Conclusion

The Linear Regression model achieved an **R² score of 0.8387**, explaining approximately **83.87% of the variation in house prices** on the test dataset.

This project provided practical experience in **data analysis, preprocessing, feature engineering, machine learning, model evaluation, and visualization**.

---

## 👤 Author

**Prathamesh Jangam**

**Track:** Data Analytics

**Task:** House Price Prediction using Linear Regression

---

## ⭐ Acknowledgement

This project was completed as part of the **Oasis Infobyte Internship Program**.

**Oasis Infobyte — Data Analytics Internship**
