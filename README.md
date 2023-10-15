# WHY IS SO EXPENSIVE TO BE ALIVE?

Living in the modern world comes with its costs. But what factors truly influence the cost of living across different regions in the U.S.? This project dives deep into understanding the intricacies of living expenses.

## Table of Contents
- [Objective](#objective)
- [Questions Addressed](#questions-addressed)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Model Building & Evaluation](#model-building--evaluation)
- [Conclusions & Insights](#conclusions--insights)

## Objective
Our primary aim was to understand the elements affecting the cost of living across various regions in the U.S. We aspired to build a regression model that predicts the total cost of living based on multiple factors.

## Questions Addressed
1. How do different components, such as housing, transportation, and healthcare, contribute to the overall cost of living?
2. Are there specific states or metropolitan areas that inherently have a higher cost of living?

## Exploratory Data Analysis
- **Data Overview**: We began with a comprehensive exploration of the dataset, understanding its structure, features, and distributions.
- **Correlation Analysis**: Found strong positive correlations between `total_cost` and various individual cost components.
- **Visualizations**: Visualized the distribution of numeric features, checked boxplots for key features, and explored categorical features.

## Data Preprocessing
- **Handling Missing Values**: Imputed missing values in `median_family_income` using median values.
- **One-Hot Encoding**: Transformed categorical variables for regression analysis.

## Model Building & Evaluation
- **Multiple Linear Regression**: Used this model to predict the `total_cost` based on selected features.
- **Performance Metrics**: Achieved an R-squared value of 1.0 on test data, indicating high predictive capability.
- **Residual Analysis**: Residuals were found to be randomly scattered, confirming the model's assumptions.

## Conclusions & Insights
- **Influencing Factors**: Components such as housing, transportation, and healthcare significantly determine the cost of living.
- **Geographical Differences**: Specific states and metropolitan areas exhibit unique cost profiles, suggesting that regional factors are essential.
- **Applications**: The model's insights can guide budget planning, policy-making decisions, and strategies for real estate developers.

---

Feel free to clone, fork, or star this repository. Contributions and feedback are always welcome!
