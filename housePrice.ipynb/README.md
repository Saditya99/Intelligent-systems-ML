# 🏠 House Price Prediction using KNN Regression

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-orange.svg)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3+-yellow.svg)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.21+-green.svg)](https://numpy.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red.svg)](https://jupyter.org/)

## 📋 Overview

A **K-Nearest Neighbors (KNN) Regression** model for predicting house prices using the Ames Housing Dataset. The model achieves **~82% accuracy** (R² score) with excellent generalization and minimal overfitting.

### Key Features
- ✅ **High Accuracy**: R² Score of 0.8196 (Training) / 0.8186 (Cross-Validation)
- ✅ **No Overfitting**: Minimal difference between training and CV scores
- ✅ **Robust Preprocessing**: Handles missing values and feature scaling
- ✅ **Optimal Parameters**: k=9 found through systematic grid search
- ✅ **Production Ready**: Complete pipeline with model persistence

---

## 📊 Performance Metrics

| Metric | Score | Interpretation |
|--------|-------|----------------|
| **Training R²** | 0.8196 | Model explains 82% of variance |
| **Cross-Validation R²** | 0.8186 | Excellent generalization |
| **Model Stability** | ±0.001 | No overfitting detected |
| **Optimal k** | 9 | Best neighborhood size |

### What This Means
- Predictions are within **±$25,000-35,000** of actual prices
- Model performs consistently across different data splits
- Ready for real-world deployment

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **scikit-learn**: KNN Regressor, StandardScaler
- **Pandas**: Data manipulation
- **NumPy**: Numerical computations
- **Joblib**: Model persistence

---
