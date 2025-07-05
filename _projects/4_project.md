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

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
