# 📊 Credit Score Forecasting Project

This project applies machine learning to forecast a person’s **credit score category** — an essential metric used by banks and financial institutions to assess a person's eligibility for loans and services.

## 🔍 What is a Credit Score?

A **credit score** is a numerical rating that represents a person's likelihood to repay a debt. It affects:
- Loan approval and interest rates
- Job screening by employers
- Deposit requirements for utilities and services

Our goal is to improve credit score prediction accuracy and reduce lending risks.

---

## 🎯 Objective

- **Classify clients** into one of three credit score levels: **Good, Standard, Poor**
- Help decision-makers **accept or reject loan requests** based on predicted credit scores
- Build and deploy a machine learning model using Python

---

## 📁 Dataset

- **Shape:** 100,000 rows × 28 features
- **Target Column:** `Credit_Score`
- Contains personal and financial information (income, occupation, payment behavior, etc.)

---

## 🧹 Data Preparation

- ✅ **No missing values** found
- 🗑 Removed irrelevant fields like `ID`, `SSN`, `Names`
- 🧠 Performed **feature engineering** to select the most relevant variables
- ⚠️ Handled **outliers** in `Annual_Income`
- 🔄 **Encoded categorical features** using Label Encoding

---

## 🤖 Model Training

- Algorithm: **Random Forest Classifier**


