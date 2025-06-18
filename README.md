# 🚗 Insurance Risk Modeling & Premium Optimization

This project focuses on building statistical and machine learning models to analyze and predict insurance claim risks and optimize premium pricing strategies. The dataset includes policyholder and vehicle attributes, as well as claim and premium data.

---

## 📌 Problem Statement

Insurance companies need to:
- Estimate **claim severity** and **claim frequency**
- Understand **risk differences** across demographics and regions
- Optimize premium pricing to balance risk, profitability, and competitiveness

---

## 🎯 Project Goals

1. **Risk Prediction**:
   - Predict probability of a claim (classification)
   - Predict claim severity for policies with claims (regression)

2. **Premium Optimization**:
   - Predict premiums using calculated risk
   - Conceptual model:  
     `Premium = (P(Claim) × Predicted Severity) + Expense Loading + Profit Margin`

3. **Statistical Testing**:
   - Test for risk/margin differences across:
     - Provinces
     - Zip codes
     - Gender

---

## 🔍 Key Features

- ✅ Data Cleaning & EDA
- ✅ A/B Testing & Hypothesis Testing (Z-test, T-test)
- ✅ Modeling with:
  - Logistic Regression
  - Random Forest
  - XGBoost
- ✅ Evaluation Metrics: Accuracy, F1-Score, RMSE, R²
- ✅ Feature Importance with SHAP (interpretable ML)
- ✅ Reproducible ML Workflow with DVC
- ✅ Visualizations: Heatmaps, Histograms, Boxplots, Temporal Trends

---

## 📦 Project Structure

