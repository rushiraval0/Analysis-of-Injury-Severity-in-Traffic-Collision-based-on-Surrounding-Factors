# Analysis of Injury Severity in Traffic Collision based on Surrounding Factors
<img src="accident.jpeg" alt="thumbnail" width="50%">

## Overview
This repository contains an analysis of injury severity in traffic collisions based on surrounding factors using the Traffic Collision dataset from Ottawa's website. The analysis aims to understand how factors such as location type, road conditions, lighting, and environmental conditions affect injury severity.

## Methods
The analysis employs various statistical techniques including linear regression, multiple linear regression, ordinal logistic regression, and decision tree methods to model injury severity based on selected predictors. Feature selection, model comparison, and Bayesian approaches were utilized to refine the models.

## Results
### Linear Regression
Linear regression identified key predictors such as Traffic Control, Light, Road Surface Condition, Initial Impact Type, and Classification of Accident.

### Multiple Linear Regression
Different model configurations were explored, with improvements observed in predictive accuracy, particularly achieving an R-squared value of 18%.

### Ordinal Logistic Regression
Employing ordinal logistic regression revealed significant coefficients indicating relationships between predictor variables and injury severity. Notably, accidents occurring later in the day and specific initial impact types were associated with higher injury severity.

### Decision Tree
The decision tree method achieved a 61% accuracy rate in predicting injury severity, highlighting its efficacy in capturing non-linear relationships among variables.

## Discussion
The analysis unveiled associations between predictor variables and injury severity in traffic collisions. Nighttime accidents, certain initial impacts, and poor road conditions were linked to greater injury severity, while factors like traffic control, lighting, and environmental conditions had smaller effects. Insights from the analysis can inform interventions aimed at reducing the severity of injuries in road accidents.

## Usage
To replicate the analysis:
1. Clone this repository.
2. Install the required dependencies.
3. Run the .rmd file in R Studio.
