---
layout: page
title: Residential Market Price Prediction System
description: Property Price Prediction and Factor Analysis Using KNN Regression
img: assets/img/housing_project.jpg
importance: 4
category: research
related_publications: false
---

## Project Overview

This project built a residential market price prediction system based on the K-Nearest Neighbors (KNN) regression algorithm. Through advanced feature engineering and machine learning techniques, it achieves accurate prediction of property prices and in-depth analysis of key factors influencing housing prices.

## Core Technical Methods

### Feature Engineering
- **Regular Expression Processing**: Extracting key feature information from property description text
- **Text Mining**: Analyzing property descriptions using natural language processing techniques
- **Feature Selection**: Screening the most influential variables for price prediction

### Data Preprocessing
- **One-Hot Encoding**: Processing categorical variables into numerical features
- **Data Standardization**: Ensuring comparability between features of different scales
- **Missing Value Handling**: Using multiple strategies to address data missing problems

### Model Building and Optimization
- **KNN Regression Model**: Non-parametric regression method based on similarity principles
- **K-Value Optimization**: Determining optimal K value through systematic grid search
- **Cross-Validation**: Using 10-fold cross-validation to ensure model robustness

## Technical Implementation

### Data Processing Technologies
- **R Language**: Main programming language and analysis environment
- **caret Package**: Machine learning model training and evaluation
- **grepl Function**: Regular expression matching and text processing
- **tidyverse**: Data cleaning and processing ecosystem

### Model Validation
- **Grid Search**: Systematically searching for optimal hyperparameter combinations
- **Cross-Validation**: Multiple validations ensuring model generalization ability
- **Performance Evaluation**: Using multiple metrics to evaluate prediction accuracy

## Feature Engineering Highlights

### Text Feature Extraction
- **Property Description Parsing**: Extracting structured information from unstructured text
- **Keyword Identification**: Identifying key descriptive terms affecting property prices
- **Feature Combination**: Creating composite features to enhance prediction capability

### Numerical Feature Processing
- **Normalization**: Ensuring reasonable allocation of feature weights
- **Outlier Handling**: Identifying and processing anomalous data points
- **Feature Scaling**: Optimizing distance calculation in KNN algorithm

## Model Performance and Validation

### Rigorous Validation Process
- **10-Fold Cross-Validation**: Ensuring model stability across different data subsets
- **Parameter Tuning**: Finding optimal K value through grid search
- **Performance Benchmarking**: Comparative validation with other regression models

### Prediction Accuracy
- **Low Prediction Error**: Achieving high accuracy in property price prediction
- **Model Robustness**: Maintaining good performance under different market conditions
- **Generalization Capability**: Good predictive effect on new data

## Factor Analysis

### Key Influencing Factors
- **Geographic Location**: Decisive influence of location on property prices
- **Property Characteristics**: Structural features such as area, number of rooms, facilities
- **Market Environment**: Surrounding amenities and market supply-demand conditions

### Business Insights
- **Price Trends**: Identifying key drivers of price changes
- **Investment Guidance**: Providing data support for property investment decisions
- **Market Analysis**: In-depth understanding of residential market dynamics

## Application Value

This project demonstrates the practical application value of machine learning in the real estate field. Through KNN regression models and advanced feature engineering techniques, it not only achieves accurate price prediction but more importantly provides a scientific methodology for real estate market analysis, offering significant practical value for property investment and market evaluation.
