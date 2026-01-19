# Loan Default Prediction — LendingClub

This repository contains a machine learning project that predicts whether a loan will default using publicly available LendingClub loan data. The analysis and modeling workflow are implemented in a Jupyter notebook with data cleaning, feature engineering, model training and evaluation.

## 📁 Repository contents

- **Accepted_loans_training_Lending_Club.ipynb** — Main notebook with data exploration, preprocessing, model building and evaluation.
- **graphs/** — Visualizations generated during analysis.
- **results/** — Outputs such as model metrics, evaluation charts, and saved artifacts.

## 🧠 What’s included

This project covers:
- Exploratory Data Analysis (EDA)
- Feature preprocessing and handling missing values
- Training and evaluating classification models
- Assessing performance with metrics like ROC AUC, Precision, Accuracy, F1 Score, and Recall
- Visualization of results and insights

## Models Trained and Evaluated

- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **XGBOOST**
- **LightGBM**
- **Stochastic Gradient Descent**
- **Naive Bayes Classifier**

Along with the models, as the dataset has an inconsistent class weight, training is done with 4 different sampling strategies:

- **Raw Dataset without any sampling strategy**
- **Class Weighted strategy - Scikit-learn**
- **Over Sampling**
- **Under Sampling**

## Link to Dataset

https://www.kaggle.com/datasets/wordsforthewise/lending-club/data?select=accepted_2007_to_2018Q4.csv.gz


