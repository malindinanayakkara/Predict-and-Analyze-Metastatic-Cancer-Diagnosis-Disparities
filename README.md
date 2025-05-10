# WiDS Datathon 2024 - Metastatic Diagnosis Period Prediction

## 📌 Overview
This project predicts the metastatic diagnosis period (in days) for breast cancer patients using demographic, socioeconomic, clinical, and environmental data. Developed for the **WiDS (Women in Data Science) Datathon 2024 Challenge 2**, it leverages machine learning to analyze factors influencing cancer progression timelines.

## 🚀 Features
- **Advanced Feature Engineering**: Age groups, diagnosis code parsing, socioeconomic scoring
- **Multiple ML Models**: LightGBM, XGBoost, Random Forest, Gradient Boosting
- **Robust Validation**: 5-fold cross-validation
- **Explainable AI**: SHAP values and feature importance visualization
- **Ensemble Approach**: Combines predictions from all models

## 📈 Model Performance Metrics

| Model          | MAE (Days) | RMSE (Days) | R² Score  |
|----------------|------------|------------|-----------|
| LightGBM       | 120.5      | 185.2      | 0.42      |
| XGBoost        | 122.1      | 188.7      | 0.40      |
| Random Forest  | 125.3      | 192.4      | 0.38      |
| Gradient Boost | 123.7      | 190.1      | 0.39      |
| **Ensemble**   | **119.8**  | **183.9**  | **0.43**  |
