# Titanic Survival Prediction 🚢

Predicting the survival of passengers on the Titanic using machine learning.

---

## 📂 Project Overview

This project predicts whether a passenger survived the Titanic disaster based on features such as age, sex, passenger class, and family relations.

**Key Objectives:**

- Data cleaning and preprocessing
- Feature engineering (FamilySize, IsAlone, Title, AgeGroup, FareCategory, Deck)
- Exploratory Data Analysis (EDA)
- Model building using Random Forest with hyperparameter tuning
- Evaluation using accuracy, confusion matrix, classification report, and ROC-AUC
- Generate submission file for Kaggle

---

## 🛠️ Technologies & Libraries

- Python 3.x  
- pandas >=2.0.0  
- numpy >=1.25.0  
- matplotlib >=3.8.0  
- seaborn >=0.12.0  
- scikit-learn >=1.3.0  
- jupyter >=1.0.0  

---

## 📊 Dataset

- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
- **Files used:**
  - `train.csv`
  - `test.csv`

**Columns include:**

- PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/Titanic_Survival_Prediction.git
cd Titanic_Survival_Prediction
