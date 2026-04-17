# Megaline: Telecom Behavior Classification Model

## About

Megaline mobile carrier wants to develop a system capable of analyzing consumer behavior and recommending one of their newer plans: Smart or Ultra. This project involves building a classification model that can predict the correct plan for subscribers based on their usage patterns (calls, messages, and internet data) with a target accuracy threshold of **0.75**.

## Technical Highlights

· **Data Preprocessing**: Analyzed a dataset of 3,214 users, ensuring clean features for usage metrics.

· **Model Selection**: Evaluated multiple classification algorithms, including **Decision Tree**, **Random Forest**, and **Logistic Regression**.

· **Hyperparameter Optimization**: Utilized loops to tune the max_depth for Decision Trees and n_estimators for Random Forests to find the highest validation accuracy.

· **Model Evaluation**: Achieved a final test accuracy exceeding the 0.75 requirement, with the Random Forest model emerging as the top performer.

· **Sanity Check**: Compared model performance against a baseline to ensure the predictive power was statistically significant.
