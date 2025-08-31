# 🚢 Titanic Survival Prediction

[![Python](https://img.shields.io/badge/python-3.11-blue?logo=python)](https://www.python.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![Model Accuracy](https://img.shields.io/badge/Accuracy-92%25-brightgreen)](https://github.com/pathananas2007/Titanic_Survival_Prediction)

Predicting the survival of passengers on the Titanic using **Machine Learning**. This project is based on the famous [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic).

---

## 📌 Project Overview
The goal of this project is to build a predictive model that answers the question:  
**“What kinds of people were more likely to survive the Titanic disaster?”**

Key objectives include:  

- Data cleaning & preprocessing  
- Feature engineering (`FamilySize`, `IsAlone`, `Title`, `AgeGroup`, `FareCategory`, `Deck`)  
- Exploratory Data Analysis (EDA) with visualizations  
- Model building using:
  - Random Forest (primary model)  
  - Logistic Regression, SVM, Decision Tree (for comparison)  
- Hyperparameter tuning with GridSearchCV  
- Model evaluation using accuracy, confusion matrix, classification report, and ROC-AUC  
- Generate `submission.csv` for Kaggle submission  

---

## 🛠️ Technologies & Libraries
- Python 3.x  
- pandas >= 2.0.0  
- numpy >= 1.25.0  
- matplotlib >= 3.8.0  
- seaborn >= 0.12.0  
- scikit-learn >= 1.3.0  
- jupyter >= 1.0.0  

---

## 📊 Dataset
Files used from Kaggle Titanic dataset:  

| File | Description |
|------|-------------|
| `train.csv` | Training dataset with labels (Survived) |
| `test.csv` | Test dataset (without labels) |
| `submission.csv` | Final predictions for Kaggle submission |

Columns include:  
`PassengerId`, `Survived` (target), `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

---

## 🚀 How to Run

1️⃣ **Clone this repository**  
```bash
git clone https://github.com/pathananas2007/Titanic_Survival_Prediction.git
cd Titanic_Survival_Prediction
