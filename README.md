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


![Screenshot 2023-10-15 at 11 13 33 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/afde2eac-ab07-4d26-a46d-02ee8c03712b)
![Screenshot 2023-10-15 at 11 13 46 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/04172d02-1ccc-4f96-bd1d-d301be52dfb2)
![Screenshot 2023-10-15 at 11 14 01 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/e9e2a438-c5dd-498d-9e46-cff5d9fcebe2)
![Screenshot 2023-10-15 at 11 14 15 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/9b363335-6ced-4537-a4da-1a514d187425)
![Screenshot 2023-10-15 at 11 14 30 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/f3e4f104-d1bf-477a-abce-5166898fba1b)
![Screenshot 2023-10-15 at 11 14 39 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/74668145-95ae-455a-bd2f-4586bdc5037c)
![Screenshot 2023-10-15 at 11 14 50 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/cf1cf25e-f4ed-4f2b-916d-59b734fc6ad5)
![Screenshot 2023-10-15 at 11 14 59 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/d71ad4f3-9cc8-43da-81d3-ec1228b9f8f5)
![Screenshot 2023-10-15 at 11 15 10 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/536b2496-e48d-4688-9598-de004f789957)
![Screenshot 2023-10-15 at 11 15 19 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/3d31bc48-4092-4469-81a0-33e9c524f3af)
![Screenshot 2023-10-15 at 11 15 31 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/56e1e065-8a97-4215-9ab6-72e2eea5546d)
![Screenshot 2023-10-15 at 11 15 44 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/0af98ec2-3668-49cb-8f3c-da52b1b2774f)
![Screenshot 2023-10-15 at 11 15 58 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/983618cd-0018-472d-973f-3da64c26c6a8)
![Screenshot 2023-10-15 at 11 16 10 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/f49a6e83-58c8-478a-b793-259014fad726)
![Screenshot 2023-10-15 at 11 16 23 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/de4874bc-5053-46d0-a39f-2379fcdedb5d)
![Screenshot 2023-10-15 at 11 16 36 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/6e3cfb8c-893c-4759-bc33-693f7f2d3588)
![Screenshot 2023-10-15 at 11 16 54 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/18b39f9a-916e-466c-8496-35ae3e7333af)
![Screenshot 2023-10-15 at 11 17 08 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/3cdd02ce-2034-4160-b171-01d4e4219b06)
![Screenshot 2023-10-15 at 11 17 20 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/7c3c3f4a-4039-415a-8542-10ae6c34b0ec)
![Screenshot 2023-10-15 at 11 17 37 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/5c9c029f-6cce-4483-b79d-f0f0181056f2)
![Screenshot 2023-10-15 at 11 17 51 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/129191ef-5891-4274-b38a-79370403601f)
![Screenshot 2023-10-15 at 11 18 04 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/39c710ea-3631-4ea4-ac15-87e9f02692c0)
![Screenshot 2023-10-15 at 11 18 11 PM](https://github.com/axhoang/living_costs_regression_project/assets/117322132/c0e185d4-67a4-4d82-9eb6-5c92a9f8bbcc)



Feel free to clone, fork, or star this repository. Contributions and feedback are always welcome!
