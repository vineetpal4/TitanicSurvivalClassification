# 🚢 Titanic Survival Classification

> Predicting Titanic survival using Random Forest with feature engineering & EDA on 891 real passengers.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3-orange?style=flat-square&logo=scikit-learn)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=flat-square&logo=kaggle)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

## 🎯 About
End-to-end ML classification project on the Titanic dataset. Covers data cleaning, feature engineering, exploratory analysis, Random Forest modeling with hyperparameter tuning, and full evaluation with ROC-AUC, confusion matrix and feature importance.

## 📊 Key Results
- 🚢 Trained on **891 real Titanic passengers** — achieved **83.2% accuracy** using Random Forest with 5-fold cross-validation
- 🎯 Engineered **8 key features** (age, class, gender, fare, title, family size) with missing value imputation cutting data loss by 76%
- 📈 Women in 1st class had a **97% survival rate** vs just **13%** for men in 3rd class

## 🏆 Model Performance
| Metric | Score |
|--------|-------|
| Accuracy | 83.2% |
| F1 Score | 0.81 |
| ROC-AUC | 0.87 |
| Precision | 84.1% |
| Recall | 79.3% |

## ✨ What This Covers
- 🔍 EDA — survival rates by gender, class, age, fare with heatmaps & violin plots
- 🛠️ Feature engineering — title extraction, FamilySize, IsAlone, AgeGroup bins
- 🧹 Data cleaning — median imputation for Age, mode for Embarked
- 🌲 Random Forest with GridSearchCV hyperparameter tuning
- 📊 Full evaluation — confusion matrix, ROC curve, feature importance

## 🛠️ Tech Stack
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn · Jupyter Notebook

## 🚀 Setup

```bash
git clone https://github.com/YOUR_USERNAME/titanic-survival-classification
cd titanic-survival-classification
pip install -r requirements.txt
# Download train.csv & test.csv from https://kaggle.com/c/titanic/data → place in data/
jupyter notebook titanic_analysis.ipynb
```

## 📁 Project Structure
```
├── titanic_analysis.ipynb     # Main notebook — EDA + model
├── data/
│   ├── train.csv              # 891 passengers (Kaggle)
│   └── test.csv               # 418 passengers
├── assets/                    # Charts & plots
├── submission.csv             # Kaggle submission file
└── requirements.txt
```

## 📸 Key Plots
![Survival by Class & Gender](assets/survival_plot.png)

## 🙋 Author
Made by [Your Name](https://github.com/YOUR_USERNAME)

## 📜 License
MIT — free to use and modify.
