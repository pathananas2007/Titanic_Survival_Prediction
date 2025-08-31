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
pip install -r requirements.txt
jupyter notebook titanic_model.ipynb
# or
python titanic_model.py
submission.csv
Titanic_Survival_Prediction/
├─ README.md
├─ titanic_model.ipynb
├─ train.csv
├─ test.csv
├─ requirements.txt
└─ .gitignore
images/
├─ age_distribution.png
├─ survival_by_class.png
└─ correlation_heatmap.png

---

✅ Copy and paste **this exact version** into `README.md`.  
This will render **perfectly on GitHub** with headings, bullets, and code blocks properly formatted.  

If you want, I can now guide you **step-by-step to upload your notebook, CSVs, and requirements.txt** so the repo is fully complete.  

Do you want me to do that next?
