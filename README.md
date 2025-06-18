# 🚢 Titanic - Machine Learning from Disaster

This repository contains my solution to the **Titanic: Machine Learning from Disaster** competition on [Kaggle](https://www.kaggle.com/competitions/titanic). The goal of the competition is to build a predictive model that answers the question: *"What sorts of people were more likely to survive?"* using passenger data.

---

## 🧠 Problem Statement

The sinking of the Titanic is one of the most infamous shipwrecks in history. This competition provides the opportunity to apply machine learning techniques to predict which passengers survived the tragedy.

---

## 🚀 Approach

1. **Exploratory Data Analysis (EDA):**
   - Survival rate based on gender, class, fare, age, and family members.
   - Handling missing values and outliers.

2. **Data Cleaning:**
   - Imputed missing values in `Age`, `Fare`, and `Embarked`.
   - Dropped unnecessary features like `Cabin`, `Ticket`, and `Name`.

3. **Feature Engineering:**
   - Converted categorical variables like `Sex` and `Embarked` into numeric form.
   - Created a new feature `FamilySize` from `SibSp` and `Parch`.

4. **Modeling:**
   - Trained a `RandomForestClassifier` and evaluated accuracy.
   - Tried `XGBoostClassifier` for improved performance.
   - Split training data into `train/val` to estimate generalization.

5. **Evaluation:**
   - Accuracy Score on validation set.
   - Public leaderboard score on Kaggle.

---

## 📊 Results

- ✅ Local validation accuracy: ~81%
- 🏁 Kaggle Public Score: `0.74641`
- 👤 Status: **Competition Contributor** (on Kaggle profile)

---

## 🛠 Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- scikit-learn  
- XGBoost  
- Jupyter Notebook  

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AmanKumarBhamboo/titanic-predictive-model.git
   cd titanic-predictive-model
