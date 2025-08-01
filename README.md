
# 📄 Predicting Employee Attrition During Economic Recession

## 🧠 Project Title
**Predicting Employee Attrition During Economic Recession**

---

## 📌 Overview

This project aims to predict employee attrition using a dataset provided by IBM. As organizations face challenging economic conditions, being able to anticipate which employees are likely to leave helps HR teams make informed decisions about retention strategies and workforce planning.

---

## 🎯 Objective

> Build and evaluate multiple machine learning models to **predict if an employee is likely to leave** the company based on historical and performance-related features.

---

## 📂 Dataset

- **Source**: IBM HR Analytics Employee Attrition Dataset
- **Size**: 28 columns, includes both numerical and categorical features
- **Target Column**: `Attrition` (Yes/No)

---

## 🔍 Exploratory Data Analysis (EDA)

Key insights include:
- **Younger employees** are more likely to leave.
- **New employees (less than 1 year tenure)** have higher attrition risk.
- Feature `"Behaviour"` was constant and thus removed.
- Duplicate employee IDs were dropped to clean the dataset.

---

## 🛠️ Preprocessing

- **Categorical features** were converted to numerical using `.unique()` inspection.
- **StandardScaler** was used for feature scaling, as features followed a Gaussian distribution.

---

## 🤖 Models Evaluated

The following machine learning models were trained and tested:
- ✅ Logistic Regression  
- ✅ Decision Tree Classifier  
- ✅ Random Forest Classifier  
- ✅ AdaBoost Classifier  
- ✅ Support Vector Classifier (SVC)  
- ✅ Artificial Neural Network (ANN)  
- ✅ Ensemble Voting Classifier

---

## 🧪 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC Score

---

## 📈 Results Summary

> The ensemble model performed the best by combining multiple classifiers and balancing individual weaknesses, followed closely by Random Forest and ANN.

---

## 📦 Requirements

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow or keras (for ANN)
```

Install with:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository.
2. Place the dataset in the same directory as the notebook.
3. Run the notebook `employee.attrition.ipynb` step by step.

---

## 🙏 Acknowledgements

Thanks to **IBM** for providing the open-source dataset used in this project.
