# Titanic_survival-Predictor
# 🚢 Titanic Survival Predictor

A machine learning project to predict passenger survival on the Titanic using classification algorithms: Random Forest, LightGBM as base models and then stacking them using Stacking Classifier using XGBoost as meta model. Built using Python and various data science libraries. This project is part of my learning journey in data science and machine learning.

## 🔍 Overview

The Titanic dataset is one of the most popular beginner-level datasets used in machine learning and data analysis. The objective is to predict whether a passenger survived or not, given attributes like age, sex, fare, class, and more.

This project includes:
- Data cleaning and preprocessing
- Feature engineering
- Exploratory Data Analysis (EDA)
- Handling missing values
- Model training and evaluation
- Model ensembling
- Submission file creation

---

## 📊 Dataset

The dataset used is the [Titanic dataset from Kaggle](https://www.kaggle.com/c/titanic/data), which includes the following files:

- `train.csv`: Contains labeled data with features and the target (`Survived`).
- `test.csv`: Contains unlabeled data for prediction.
- `test_target.csv`: Target variable for the test data. (Original name of the csv file in Kaggle: `gender_submission.csv`)

---

## 🧾 Features

| Feature        | Description                              |
|----------------|------------------------------------------|
| PassengerId    | Unique ID of passenger                   |
| Pclass         | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| Name           | Name of the passenger                    |
| Sex            | Gender                                   |
| Age            | Age in years                             |
| SibSp          | # of siblings/spouses aboard             |
| Parch          | # of parents/children aboard             |
| Ticket         | Ticket number                            |
| Fare           | Passenger fare                           |
| Cabin          | Cabin number                             |
| Embarked       | Port of Embarkation (C = Cherbourg, etc) |
| Survived       | Target (0 = No, 1 = Yes)                 |

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/rohankharche34/titanic-survival-predictor.git
cd titanic-survival-predictor
```

## Setup a virtual environment (if needed)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

## Install the required packages
```bash
pip install -r requirements.txt
```
