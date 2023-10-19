# WHY IS SO EXPENSIVE TO BE ALIVE?

## Introduction

Living in the modern world comes with its own set of financial challenges. From housing and healthcare to education and leisure, various factors contribute to the overall cost of living. This project aims to investigate these elements, specifically within the context of the United States, using a data-driven approach.

## Table of Contents

- [Introduction](#introduction)
- [Objective](#objective)
- [Research Questions](#research-questions)
- [Data Exploration](#data-exploration)
- [Data Preprocessing](#data-preprocessing)
- [Model Building and Evaluation](#model-building-and-evaluation)
- [Model Assumptions Verification](#model-assumptions-verification)
- [Conclusions and Recommendations](#conclusions-and-recommendations)

## Objective

The core objective of this project is to develop a robust predictive model that estimates the total cost of living in various U.S. regions. The model aims to consider multiple factors, offering a comprehensive view of what contributes to living expenses.

## Research Questions

1. What factors contribute significantly to the overall cost of living in different U.S. regions?
2. How do specific variables, such as housing, healthcare, and transportation, weigh in on the total cost of living?
3. Do certain states or metropolitan areas inherently have higher or lower costs of living?

## Data Exploration

- **Data Overview**: An initial data exploration was conducted to understand the dataset's structure, features, and distributions.
- **Correlation Analysis**: Strong correlations were identified between the total cost and individual living cost components.
- **Descriptive Statistics**: Generated descriptive statistics to summarize the central tendency, dispersion, and shape of the dataset's distribution.

![Data Exploration Screenshots](your-screenshot-links-here)

## Data Preprocessing

- **Missing Data**: Handled missing values in `median_family_income` by imputation.
- **Categorical Encoding**: Utilized one-hot encoding for categorical variables, making them suitable for regression analysis.

![Data Preprocessing Screenshots](your-screenshot-links-here)

## Model Building and Evaluation

- **Algorithm Choice**: Adopted Multiple Linear Regression for its interpretability and effectiveness in dealing with multiple predictors.
- **Performance Metrics**: Achieved an R-squared value close to 1.0, indicating the model's high predictive accuracy.
- **Feature Importance**: Identified key features that significantly impact the total living cost.

![actual_vs_preidcted](https://github.com/axhoang/living_costs_regression_project/assets/117322132/0ccff218-7ec9-43c8-817a-79bd3eaf220b)
![RESIDUALS_VS_PREDICTEDVALUES](https://github.com/axhoang/living_costs_regression_project/assets/117322132/681ca414-fdcf-47d8-9e22-488f2f2472b6)
![qq_plot](https://github.com/axhoang/living_costs_regression_project/assets/117322132/0daf15af-c06f-493c-bc0f-e5b9fc69dfaf)

## Model Assumptions Verification

- **Linearity and Homoscedasticity**: Verified through residual plots.
- **Independence**: Assessed using the Durbin-Watson test, which indicated no significant autocorrelation.
- **Normality**: Confirmed through Q-Q plots.

![regression_assumption_check_4](https://github.com/axhoang/living_costs_regression_project/assets/117322132/7232c975-9808-4cc2-9bbe-bbc237ef4236)

## Conclusions and Recommendations

- **Key Factors**: Housing, healthcare, and transportation were found to be significant determinants of the cost of living.
- **Regional Variations**: Certain states and metropolitan areas exhibit unique cost structures.
- **Policy Implications**: These insights could be invaluable for policymakers, urban planners, and individuals looking to relocate.

![conclusion](https://github.com/axhoang/living_costs_regression_project/assets/117322132/cd817dd0-07b0-4b2d-bb09-a67eafe5176d)
