# Product-Market-Type-Classification
This project aims to classify retail products into different market types using machine learning. We built a supervised classification model based on the XGBoost algorithm, which demonstrated high accuracy in predicting the appropriate market type based on product and outlet features.
# 🛒 Product Market Type Classification

This project uses machine learning (XGBoost) to predict the **market type** of retail products based on their features. It was developed for the **ECE3403 - Data Analytics & Optimization** course at AASTMT.

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


