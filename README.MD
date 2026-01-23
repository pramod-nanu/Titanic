# Titanic Survival Prediction (Kaggle)

## 📌 Project Overview
This project solves the Kaggle Titanic – Machine Learning from Disaster competition.
The goal is to predict whether a passenger survived the Titanic disaster using
machine learning techniques.

---

## 📂 Dataset
- Source: Kaggle Titanic Competition
- Files used:
  - train.csv
  - test.csv

---

## 🔍 Exploratory Data Analysis (EDA)
- Analyzed survival rate by:
  - Gender
  - Passenger Class
  - Age distribution
- Key observation:
  - Females had significantly higher survival rates
  - First-class passengers survived more than others

---

## 🛠️ Feature Engineering
- Converted `Sex` to numeric (male=0, female=1)
- Filled missing `Age` values using median from training data
- Created new feature:
  - `FamilySize = SibSp + Parch + 1`
- Selected final features:
  - Pclass
  - Sex
  - Age
  - FamilySize

---

## 🤖 Models Used
- Logistic Regression (Baseline)
- Decision Tree Classifier
- Random Forest Classifier
- Hyperparameter tuning using GridSearchCV

---

## 📊 Model Performance

| Model | Accuracy | F1 Score |
|-----|----------|----------|
| Logistic Regression | ~0.80 | ~0.75 |
| Decision Tree | ~0.78 | ~0.78 |
| Random Forest | ~0.81 | ~0.77 |

---

## 🏆 Kaggle Result
- Public Leaderboard Score: **0.77751**
- Submission file generated with:
  - PassengerId
  - Survived

---

## 🧠 Key Learnings
- Importance of feature engineering over model complexity
- Avoiding data leakage by using training statistics only
- Using accuracy and F1-score for model comparison
- End-to-end ML workflow from EDA to Kaggle submission

---

## 🚀 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📎 How to Run
1. Clone the repository
2. Install required libraries
3. Run the notebook in order

---

## 👤 Author
Pramod Gaikwad
