# WHY IS IT SO EXPENSIVE, TO JUST BE ALIVE?

## Introduction

Living in the modern world comes with its own set of financial challenges. From housing and healthcare to education and leisure, various factors contribute to the overall cost of living. This project aims to investigate these elements, specifically within the context of the United States, using a data-driven approach.

## Table of Contents

- [Introduction](#introduction)
- [Objective](#objective)
- [Research Questions](#research-questions)
- [Data Exploration](#data-exploration)
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


![1](https://github.com/axhoang/living_costs_regression_project/assets/117322132/3de59e09-42f8-4e1b-ab37-ad3dc1189ce0)
![2](https://github.com/axhoang/living_costs_regression_project/assets/117322132/15b7b03b-df76-41a8-b039-3c699506f929)
![Screenshot 2023-10-19 at 2 19 26 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/adb5459a-560e-4268-bfb7-d66efc912152)
![4](https://github.com/axhoang/living_costs_regression_project/assets/117322132/2991fb86-0d75-4e4c-8097-b12a23825c34)
![5](https://github.com/axhoang/living_costs_regression_project/assets/117322132/141d418d-3922-45cf-9c21-672d06e3819a)
![6](https://github.com/axhoang/living_costs_regression_project/assets/117322132/c0cd10ac-babe-434f-8dd9-2ca8ddf2d7d8)
![7](https://github.com/axhoang/living_costs_regression_project/assets/117322132/7d5f4797-f1a7-4355-b1a5-ae70acd35331)
![8](https://github.com/axhoang/living_costs_regression_project/assets/117322132/56d13ea4-9a6d-4395-8c7b-72d8c7c0b184)
![9](https://github.com/axhoang/living_costs_regression_project/assets/117322132/34e4bdd4-af46-42e1-9490-473cadb5c1f9)
![10](https://github.com/axhoang/living_costs_regression_project/assets/117322132/99f22558-4958-4c75-8b43-fd3c0b325a93)
![11](https://github.com/axhoang/living_costs_regression_project/assets/117322132/4c3fe405-0f29-4662-b644-e59a7cf0d35d)
![12](https://github.com/axhoang/living_costs_regression_project/assets/117322132/53c091d0-cb8f-4904-9cad-5f59b85bf425)
![13](https://github.com/axhoang/living_costs_regression_project/assets/117322132/1a919d25-102b-476b-b62d-87c81e6dcb2b)
![14](https://github.com/axhoang/living_costs_regression_project/assets/117322132/ed5c3d1b-1214-467d-b742-dbc75f04f0d1)
![15](https://github.com/axhoang/living_costs_regression_project/assets/117322132/b3f03c67-4365-4e96-9770-138a1c1005d4)
![16](https://github.com/axhoang/living_costs_regression_project/assets/117322132/a514989a-002b-4bb5-bcc7-6157525fde50)



## Model Building and Evaluation

- **Algorithm Choice**: Adopted Multiple Linear Regression for its interpretability and effectiveness in dealing with multiple predictors.
- **Performance Metrics**: Achieved an R-squared value close to 1.0, indicating the model's high predictive accuracy.
- **Feature Importance**: Identified key features that significantly impact the total living cost.
- **Missing Data**: Handled missing values in `median_family_income` by imputation.
- **Categorical Encoding**: Utilized one-hot encoding for categorical variables, making them suitable for regression analysis.

![Prepping_for_regression_anlalysis](https://github.com/axhoang/living_costs_regression_project/assets/117322132/92145cd5-b568-4ece-ab73-4ad2e7f2841d)
![building_the_model](https://github.com/axhoang/living_costs_regression_project/assets/117322132/e1e492a4-759b-44c1-a24c-6ba8dd16c000)
![evaluting_the_model](https://github.com/axhoang/living_costs_regression_project/assets/117322132/c9af2383-8b67-46c3-954a-0098e871c1bc)
![examinie_the_coeffeicents_1](https://github.com/axhoang/living_costs_regression_project/assets/117322132/2ce4878c-25e2-4150-aec7-783e78a9d12a)
![examine_the_co_2](https://github.com/axhoang/living_costs_regression_project/assets/117322132/cb2f3bfb-e8e7-41ba-ae57-cc1525a2ff49)


## Model Assumptions Verification

- **Linearity and Homoscedasticity**: Verified through residual plots.
- **Independence**: Assessed using the Durbin-Watson test, which indicated no significant autocorrelation.
- **Normality**: Confirmed through Q-Q plots.

![actual_vs_preidcted](https://github.com/axhoang/living_costs_regression_project/assets/117322132/0ccff218-7ec9-43c8-817a-79bd3eaf220b)
![RESIDUALS_VS_PREDICTEDVALUES](https://github.com/axhoang/living_costs_regression_project/assets/117322132/681ca414-fdcf-47d8-9e22-488f2f2472b6)
![qq_plot](https://github.com/axhoang/living_costs_regression_project/assets/117322132/0daf15af-c06f-493c-bc0f-e5b9fc69dfaf)
![regression_assumption_check_4](https://github.com/axhoang/living_costs_regression_project/assets/117322132/7232c975-9808-4cc2-9bbe-bbc237ef4236)

## Conclusions and Recommendations

- **Key Factors**: Housing, healthcare, and transportation were found to be significant determinants of the cost of living.
- **Regional Variations**: Certain states and metropolitan areas exhibit unique cost structures.
- **Policy Implications**: These insights could be invaluable for policymakers, urban planners, and individuals looking to relocate.

![conclusion](https://github.com/axhoang/living_costs_regression_project/assets/117322132/cd817dd0-07b0-4b2d-bb09-a67eafe5176d)
