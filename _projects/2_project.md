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
