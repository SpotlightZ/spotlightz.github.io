---
layout: page
title: Hospital Discharge Trend Prediction and Resource Optimization
description: A Feasibility Study Using Time Series Models
img: assets/img/hospital_project.jpg
importance: 2
category: research
related_publications: false
---

## Project Overview

This project aims to develop time series forecasting models to predict hospital discharge trends by integrating hospital financial reports and public health surveillance data, providing data support for medical resource optimization.

## Data Integration and Preprocessing

### Data Sources
- **Hospital Financial Reports**: Large-scale hospital financial data from the Centers for Medicare & Medicaid Services (CMS)
- **Public Health Surveillance Data**: Influenza-like illness (ILI) monitoring data from the Centers for Disease Control and Prevention (CDC)
- **Medical Subsidy Data**: Disproportionate Share Hospital (DSH) payment data

### Data Preprocessing
- Cleaning and standardization of large-scale heterogeneous data
- Seasonal adjustment of time series data
- Missing value handling and outlier detection

## Modeling Methods

### Time Series Models
- **ARIMA Models**: Used to capture trends and seasonal patterns in time series
- **Enhanced Linear Regression**: Incorporating exogenous variables such as ILI incidence rates, DSH payments, etc.
- **Model Comparison**: Comparative analysis of multiple predictive models' performance

### Feature Engineering
- **Seasonal Factors**: Considering seasonal variations in hospital discharges
- **Exogenous Variables**: External factors such as ILI incidence rates, government subsidies
- **Lag Features**: Time lag effects of historical data

## Key Results

### Prediction Accuracy
- **MAPE of 0.98%**: Final feature-enhanced model achieved extremely high prediction accuracy
- **Significantly Outperforming Baselines**: Superior performance compared to simple baseline models and traditional ARIMA models
- **Robustness Validation**: Ensuring model reliability through various validation methods

### Practical Value
- **Resource Allocation Optimization**: Providing discharge trend forecasting support for hospital management
- **Policy Making Reference**: Data-driven decision support for health policy makers
- **Cost-Benefit Analysis**: Forecasting models assisting in healthcare cost control

## Technology Stack

- **Statistical Analysis**: R language and its ecosystem
- **Time Series Analysis**: auto.arima, forecast package
- **Data Visualization**: ggplot2, plotly
- **Modeling Techniques**: Linear regression (lm), time series decomposition
- **Data Processing**: dplyr, tidyverse

## Research Significance

This research demonstrates that precise prediction of hospital discharge trends can be achieved by integrating multi-source data with advanced time series modeling techniques. This provides a scientific basis for rational allocation of medical resources and optimization of healthcare systems, offering significant practical value for improving healthcare service efficiency.
