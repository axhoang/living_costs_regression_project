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


![Screenshot 2023-10-15 at 11 18 11 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/865c13e9-c19d-4932-8ecd-7d4396906ea8)
![Screenshot 2023-10-15 at 11 18 04 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/8fccbb8a-a8c9-458f-9e96-6e57f47b2dac)
![Screenshot 2023-10-15 at 11 17 51 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/1c70220f-d69d-4d69-9aa7-58b193a21ff2)
![Screenshot 2023-10-15 at 11 17 37 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/ad165825-fbf3-4cf2-b0fb-cb51c424fa83)
![Screenshot 2023-10-15 at 11 17 20 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/bdc23b18-3433-43b9-8e52-04074510c357)
![Screenshot 2023-10-15 at 11 17 08 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/7dbedeef-cb86-4d3d-92db-929d193b9e5b)
![Screenshot 2023-10-15 at 11 16 54 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/434b6ff6-ca8d-4100-bb05-4d3b0cee1fdb)
![Screenshot 2023-10-15 at 11 16 36 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/c645b22c-d7db-4a78-9950-4fc41808f08b)
![Screenshot 2023-10-15 at 11 16 23 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/3c9aa645-b791-43fe-aa3e-d5ff617f97c6)
![Screenshot 2023-10-15 at 11 16 10 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/11e785b5-ba2e-4364-89cf-50d786b775f2)
![Screenshot 2023-10-15 at 11 15 58 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/55df7406-4549-4347-ac67-61f461be61c7)
![Screenshot 2023-10-15 at 11 15 44 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/fb246102-65c6-4688-b46b-25096ece8f99)
![Screenshot 2023-10-15 at 11 15 31 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/522e72be-057d-44b3-a6f5-3ef87935992e)
![Screenshot 2023-10-15 at 11 15 19 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/42b9d39d-bb06-4643-9cc1-db4eabf75386)
![Screenshot 2023-10-15 at 11 15 10 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/8eb1a529-a65c-4277-9e2f-2c797de331e2)
![Screenshot 2023-10-15 at 11 14 59 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/c0023f3c-2fac-4f37-bd46-fa2d73dde80d)
![Screenshot 2023-10-15 at 11 14 50 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/5ef162d0-b76d-4152-a0f2-722d991e9fdc)
![Screenshot 2023-10-15 at 11 14 39 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/e73ba142-1beb-4cec-a690-282c5707c61d)
![Screenshot 2023-10-15 at 11 14 30 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/ff160719-c6e7-4a81-8fa5-1baef163810e)
![Screenshot 2023-10-15 at 11 14 22 PM (3)](https://github.com/axhoang/living_costs_regression_project/assets/117322132/d8bfb929-8f45-4941-9a2f-64fa7e475dfa)
![Screenshot 2023-10-15 at 11 14 22 PM (2)](https://github.com/axhoang/living_costs_regression_project/assets/117322132/8b4f273d-f0b5-4ea8-a8d0-843a0bfdfb5a)
![Screenshot 2023-10-15 at 11 14 22 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/fa8dbdf4-8e6d-4e14-82ba-f0fec844fd83)
![Screenshot 2023-10-15 at 11 14 15 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/c5ed6beb-a274-48c5-a40e-e56918ad0766)
![Screenshot 2023-10-15 at 11 14 01 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/091117d8-db72-4a33-a9b9-585bdfbdc89c)
![Screenshot 2023-10-15 at 11 13 46 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/974fc7fc-029e-4be9-99f3-3d4858097c89)
![Screenshot 2023-10-15 at 11 13 33 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/c75a4e1a-1648-40fd-8688-3fed990ecd9a)


Feel free to clone, fork, or star this repository. Contributions and feedback are always welcome!
