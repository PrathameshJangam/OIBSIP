# 🍷 Wine Quality Prediction

## 📌 Overview

This project aims to predict wine quality based on its physicochemical properties using machine learning classification algorithms.

The project uses the **Wine Quality Dataset** from the **UCI Machine Learning Repository**. The dataset contains chemical properties such as acidity, residual sugar, chlorides, density, pH, sulphates, and alcohol.

The original wine quality score contains multiple classes and is not evenly distributed. Therefore, the quality score was converted into a **binary classification problem**:

- **Bad Wine:** Quality < 6
- **Good Wine:** Quality ≥ 6

Three classification algorithms were trained and compared:

- Random Forest Classifier
- Support Vector Classifier (SVC)
- Stochastic Gradient Descent (SGD) Classifier

---

## 🎯 Objectives

The main objectives of this project are:

- Explore and understand the Wine Quality dataset.
- Analyze the distribution of wine quality scores.
- Identify class imbalance.
- Perform Exploratory Data Analysis (EDA).
- Visualize the distributions of chemical features.
- Analyze feature correlations using a heatmap.
- Convert wine quality scores into binary classes.
- Perform a stratified train-test split.
- Apply feature scaling where required.
- Train three classification models.
- Evaluate model performance using multiple metrics.
- Compare the performance of all three models.
- Analyze feature importance using Random Forest.
- Select the best-performing model.

---

## 📊 Dataset

### Source

**UCI Machine Learning Repository – Wine Quality Dataset**

https://archive.ics.uci.edu/dataset/186/wine+quality

This project uses the **red wine dataset (`winequality-red.csv`)**.

### Dataset Features

The dataset contains the following physicochemical properties:

| Feature | Description |
|---|---|
| `fixed acidity` | Amount of fixed acids in the wine |
| `volatile acidity` | Amount of volatile acids in the wine |
| `citric acid` | Amount of citric acid in the wine |
| `residual sugar` | Amount of residual sugar |
| `chlorides` | Amount of salt in the wine |
| `free sulfur dioxide` | Free sulfur dioxide level |
| `total sulfur dioxide` | Total sulfur dioxide level |
| `density` | Density of the wine |
| `pH` | Acidity level |
| `sulphates` | Sulphate concentration |
| `alcohol` | Alcohol percentage |

### Target Variable

The original target variable is:

Quality

---

## 🔄 Project Workflow

The project follows a complete machine learning workflow from data collection and exploration to model training, evaluation, comparison, and final model selection.

Dataset → Data Loading → Data Inspection → Data Cleaning → Exploratory Data Analysis (EDA) → Class Distribution Analysis → Feature Engineering → Train-Test Split → Feature Scaling → Model Training → Model Evaluation → Model Comparison → Feature Importance Analysis → Final Model Selection

---

## 🏆 Conclusion

Three machine learning classification models were trained and compared to predict whether a wine belongs to the **Bad** or **Good** quality category.

The models achieved the following accuracy scores:

| Rank | Model | Accuracy |
|---:|---|---:|
| 🥇 1 | **Random Forest** | **81.56%** |
| 🥈 2 | **SVC** | **76.25%** |
| 🥉 3 | **SGD Classifier** | **65.63%** |

Based on the results, **Random Forest performed the best**, achieving an accuracy of **81.56%**.

SVC achieved **76.25%**, while SGD Classifier achieved **65.63%**.

Therefore, **Random Forest is selected as the preferred model for this project** because it provided the highest accuracy among the three evaluated models. Additionally, Random Forest provides feature importance values, which help in understanding the relative contribution of different physicochemical features to the model's predictions.

For real-world deployment, accuracy should not be considered alone. Precision, recall, F1-score, confusion matrix results, class imbalance, computational requirements, and the specific business/application requirements should also be considered.

---

## 👤 Author

**Prathamesh Jangam**

**Track:** Data Analytics

**Task:** Wine Quality Prediction 

---

## ⭐ Acknowledgement

This project was completed as part of the **Oasis Infobyte Internship Program**.

**Oasis Infobyte — Data Analytics Internship**

---

⭐ **If you found this project useful, feel free to star the repository!**

