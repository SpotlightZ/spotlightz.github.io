---
layout: page
title: FLoRA Dialogue Usefulness Score Prediction
description: Comprehensive Feature Engineering and XGBoost Model Optimization
img: assets/img/flora_project.jpg
importance: 1
category: research
related_publications: false
---

## Project Overview

This project focuses on comprehensive feature engineering and predictive analysis from raw chatbot-student dialogue data, aiming to model interaction quality and predict dialogue usefulness scores.

## Core Technologies and Methods

### Feature Engineering
- **Structural Features**: Dialogue turn count, word ratio, sentence length, etc.
- **Semantic Features**: TF-IDF vectorization, weighted keyword extraction, Principal Component Analysis (PCA) dimensionality reduction

### Model Development
- **XGBoost Model**: Hyperparameter optimization using grid search and cross-validation
- **Performance Improvement**: 20.79% improvement in RMSE and 22% improvement in MAE compared to baseline prediction results

### Model Interpretability
- **SHAP Analysis**: Providing local and global model prediction interpretability
- **Feature Importance**: In-depth analysis combining XGBoost's built-in feature importance and SHAP values

## Key Achievements

1. **Significant Performance Enhancement**: Model prediction accuracy greatly improved through carefully designed feature engineering
2. **Enhanced Interpretability**: SHAP framework makes the model decision process transparent
3. **Practical Validation**: Providing an effective tool for dialogue quality assessment in educational technology

## Technology Stack

- **Machine Learning**: XGBoost, Random Forest, Linear Regression
- **Data Processing**: Python, Pandas, NumPy
- **Feature Engineering**: Scikit-learn, TF-IDF, PCA
- **Interpretability**: SHAP
- **Validation Methods**: Cross-validation, Grid Search

## Research Significance

This project provides new approaches for automatically evaluating the quality of educational dialogues. By combining structural and semantic features, it enables more accurate prediction of educational value in dialogues. This has important implications for improving interactive experiences in online education platforms.

