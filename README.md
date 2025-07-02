# Product-Market-Type-Classification
This project aims to classify retail products into different market types using machine learning. We built a supervised classification model based on the XGBoost algorithm, which demonstrated high accuracy in predicting the appropriate market type based on product and outlet features.

## 🔍 Project Goal
To automatically classify products into one of four market types using product and outlet data.

## 📊 Dataset Features
- **Product Info**: ID, weight, fat content, visibility, type, MRP
- **Outlet Info**: ID, establishment year, size, tier
- **Target**: Market type (4 classes)

## ⚙️ What We Did
- Cleaned and preprocessed the data
- Handled missing values, class imbalance (SMOTE), and feature leakage
- Used one-hot encoding for categorical features
- Trained an XGBoost classifier
- Evaluated results using accuracy and confusion matrix

## 🏁 Dataset Source

This project is based on a dataset from a real **Kaggle competition** on product market classification.  
We developed and ran our notebook on (https://www.kaggle.com/competitions/pr-21-competition-classification/overview), which provided GPU/CPU resources and competition leaderboard scoring.

> **Before Preprocessing Accuracy**: 68.705%  
> **After Preprocessing Accuracy**: 99.251%
> ## 👨‍💻 Collaborators
- [Salma Fayed](https://github.com/salmafayed7)
