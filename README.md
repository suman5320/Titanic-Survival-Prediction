# 🛳️ Titanic Survival Prediction

Predict the survival of passengers on the Titanic using machine learning. This project walks through a complete pipeline — from data analysis and cleaning to building and evaluating a logistic regression model.

---

## 📌 Overview

This notebook-based project includes:

- 🧹 Data cleaning & preprocessing
- 📊 Exploratory Data Analysis (EDA)
- 🧠 Feature engineering
- 🤖 Logistic Regression model
- 📈 Model evaluation with metrics

All implemented using Python libraries — ideal for beginners getting started with ML.

---

## 🗂️ Project Structure

---

## 🔍 Dataset

- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic)
- Contains demographic and travel information of passengers.
- Target variable: `Survived` (1 = survived, 0 = died)

---

## 🧰 Libraries Used

- `pandas` — data handling
- `numpy` — numerical operations
- `matplotlib`, `seaborn` — visualization
- `scikit-learn` — modeling and evaluation

---

## 📊 Features Considered

| Feature        | Description                        |
|----------------|------------------------------------|
| `Pclass`       | Ticket class (1 = 1st, 2 = 2nd, etc.) |
| `Sex`          | Gender of the passenger             |
| `Age`          | Age in years                        |
| `SibSp`        | Siblings/spouses aboard             |
| `Parch`        | Parents/children aboard             |
| `Fare`         | Ticket price                        |
| `Embarked`     | Port of embarkation                 |
| `FamilySize`   | Engineered feature: SibSp + Parch + 1 |

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction

