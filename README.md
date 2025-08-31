# 🚢 Titanic Survival Prediction  

Predicting the survival of passengers on the Titanic using **Machine Learning**.  
This project is based on the famous [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic).  

---

## 📌 Project Overview  
The goal is to build a predictive model that answers the question:  
**"What sorts of people were more likely to survive the Titanic disaster?"**  

### Key Objectives:  
- Data cleaning & preprocessing  
- Feature engineering (FamilySize, IsAlone, Title, AgeGroup, FareCategory, Deck)  
- Exploratory Data Analysis (EDA) with visualizations  
- Model building with:  
  - Random Forest (primary model)  
  - Logistic Regression, SVM, Decision Tree (for comparison)  
- Hyperparameter tuning with GridSearchCV  
- Model evaluation (accuracy, confusion matrix, ROC-AUC, classification report)  
- Generate final **submission.csv** for Kaggle  

---

## 🛠️ Technologies & Libraries  
- Python 3.x  
- pandas ≥ 2.0.0  
- numpy ≥ 1.25.0  
- matplotlib ≥ 3.8.0  
- seaborn ≥ 0.12.0  
- scikit-learn ≥ 1.3.0  
- jupyter ≥ 1.0.0  

---

## 📊 Dataset  
- **train.csv** → Training dataset with labels (`Survived`)  
- **test.csv** → Test dataset (without labels)  
- **submission.csv** → Final predictions for Kaggle submission  

### Columns include:  
- PassengerId  
- Survived (target variable)  
- Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked  

---

## 🚀 How to Run  

1️⃣ Clone this repository  
```bash
git clone https://github.com/pathananas2007/Titanic_Survival_Prediction.git
cd Titanic_Survival_Prediction
