# Car Insurance Loans

Author:
Yaman Shadid

## Introduction

The objective is to identify which customer will claim his/her loan.

## Data

The dataset used in this project contains information about various individuals and their relevant driving information.

## Methods

1. **Data Collection and Source Selection:** The data was collected from [Car Insurance Data](https://www.kaggle.com/datasets/sagnik1511/car-insurance-data), which was chosen based on its relevance and reliability for the project's objectives.

2. **Data Cleaning:** The collected data underwent thorough cleaning to handle missing values, outliers, and inconsistencies to ensure the data's quality and integrity.

## Key Visuals

![download](https://github.com/Yaman-Shadid/Car_Sales/assets/116229037/d51d56f8-56cb-487f-ab8b-84a443adc99f)

This plot displays the relationship between the Past Accidents of drivers and their current number of Speeding Violations. The data shows that the Speeding Violations are higher the lower the Past Accidents. This may suggest that drivers are more careful over time because of their frequent violations, so it lessens their accidents.

![download (1)](https://github.com/Yaman-Shadid/Car_Sales/assets/116229037/a869bbc5-969e-4d82-93c7-b3bad9f3ec78)

This plot displays the relationship between the DUIS of drivers and their current number of Speeding Violations. The data shows that the Speeding Violations are higher the lower the DUIS. May suggest that drivers are also more careful over time because of their frequent violations, so it lessens their accidents.

## Models

Utilizing a **Decision Tree Classifier** and **KNN**, I conducted outcome predictions, achieving an accuracy of 72% on the Decision Tree Classifier model. Suggesting that the model is correct about 72% of the time in its predictions. Whether this level of accuracy is acceptable or not depends on the specific goals and requirements of the stakeholders. It's important to consider the trade-offs between precision, recall, and accuracy based on their application's needs and constraints.

Given that the dataset contains binary outcomes (0 or 1), accuracy is important because it tells you the overall percentage of correct predictions made by my model.

In many scenarios, especially in areas like medical diagnosis, fraud detection, or quality control, the cost of misclassification can vary for different classes. In such cases, accuracy alone may not provide a complete picture of model performance.

However, in cases where there is no significant class imbalance, and the cost of misclassification for both classes is roughly equal, accuracy can be a meaningful and interpretable metric. It gives you a straightforward measure of how well your model is doing overall.

In summary, while precision, recall, and F1-score are valuable for understanding class-specific performance, accuracy remains an essential metric to gauge overall model effectiveness, especially when dealing with a binary outcome like 0 or 1, provided that there's no significant class imbalance or varying misclassification costs.

## Reccomendations

To determine the practical value of this accuracy rate, stakeholders should evaluate the specific context of their application. Understanding that there are trade-offs between precision, recall, and accuracy. Depending on the stakeholders' objectives, I may need to adjust the model's parameters or choose a different algorithm to optimize these metrics accordingly. It's advisable to work closely with domain experts to make informed decisions about model performance, especially when dealing with binary outcomes like 0 or 1 in scenarios with varying costs and class imbalances.
