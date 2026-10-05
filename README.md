# Diabetes Prediction using Logistic Regression

## 📌 Project Overview

This project predicts diabetes using the Pima Indians Diabetes Dataset and Logistic Regression.

## 🎯 Objective

The objective is to predict whether a person has diabetes:

- `0` = No Diabetes
- `1` = Diabetes

## 📊 Dataset

Dataset: Pima Indians Diabetes Dataset

Features used:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

Target: Outcome

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 🤖 Machine Learning Model

**Logistic Regression**

Preprocessing:

- Invalid zero values replaced with missing values
- Median imputation
- StandardScaler
- Balanced Logistic Regression

## 📈 Results

| Metric | Score |
|---|---:|
| Accuracy | 73.4% |
| Precision | 60.3% |
| Recall | 70.4% |
| F1-Score | 65.0% |
| ROC-AUC | 81.3% |

## 📌 Confusion Matrix

- True Negative (TN): 75
- False Positive (FP): 25
- False Negative (FN): 16
- True Positive (TP): 38

## 🔍 Key Findings

Glucose and BMI showed strong positive model coefficients. The model achieved a ROC-AUC of 0.813 and detected approximately 70.4% of positive cases in the test data.

## ⚠️ Limitation

This project is intended for learning machine learning classification concepts and is not a medical diagnosis system.

## 📁 Project File

`Diabetes_Prediction_Logistic_Regression.ipynb`
