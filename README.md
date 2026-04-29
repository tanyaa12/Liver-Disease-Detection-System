# Liver-Disease-Detection-System

# 🩺 Early Prediction of Liver Disease Using Machine Learning

## 📌 Overview

This project focuses on predicting liver disease using machine learning techniques. The goal is to develop an accurate and efficient model that can assist in early diagnosis and support clinical decision-making.

---

## 🎯 Objectives

* Predict liver disease using clinical patient data
* Compare performance of multiple machine learning models
* Improve accuracy using feature engineering and feature selection
* Handle challenges like class imbalance and data preprocessing

---

## 📊 Dataset

* Source: Kaggle (Liver Patient Dataset)
* Total Records: ~30,000
* Features: 11 (Age, Gender, Bilirubin, Enzymes, Proteins, etc.)
* Target:

  * `1` → Liver Disease
  * `0` → No Liver Disease

---

## ⚙️ Methodology

1. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical features
   * Outlier removal using Z-score
   * Train/Validation/Test split (70:10:20)

2. **Handling Class Imbalance**

   * Bootstrapping applied
   * Balanced dataset (18,000 : 15,000)

3. **Feature Engineering**

   * Polynomial features (Bilirubin)
   * Ratio features (Albumin / Proteins)
   * Log transformation

4. **Feature Selection**

   * Recursive Feature Elimination (RFE)
   * Selected top 6 features

---

## 🤖 Models Used

* Naive Bayes
* Logistic Regression
* Random Forest
* Decision Tree
* XGBoost
* Support Vector Machine (SVM)
* Multi-Layer Perceptron (MLP)
