# Laptop Price Prediction

## Overview
This project focuses on predicting laptop prices using machine learning techniques. The dataset used for this project contains various features such as company, product name, specifications, and price in euros/rupees. The goal is to develop models that can accurately predict the price of a laptop based on its features.

## Data Preprocessing
- Data preprocessing for this project was particularly challenging due to the complex textual nature of the dataset.
- The dataset was loaded using pandas, and initial exploratory data analysis was performed.
- Data cleaning steps were implemented to handle missing values and outliers.
- Categorical variables were encoded using one-hot encoding.
- Feature engineering techniques were applied to extract relevant information from textual data.
- Data was transformed and prepared for modeling.

## Model Selection
Two machine learning algorithms were explored for modeling:
1. **Decision Tree Regressor**
   - Decision tree regression was implemented to predict laptop prices.
   - Hyperparameter tuning was performed to optimize model performance.
   - The best-performing model achieved an accuracy of approximately 81.67%.

2. **Random Forest Regressor**
   - Random forest regression was employed as an alternative modeling approach.
   - The model was trained and evaluated, achieving an accuracy of approximately 81.64%.

## Deployment
The best-performing model, the Decision Tree Regressor, was selected for deployment.
The trained model was saved using the pickle library for future use.

## Conclusion
This project demonstrates the application of machine learning techniques in predicting laptop prices based on their specifications. The developed models can assist consumers in making informed decisions and provide valuable insights to laptop manufacturers.

**Created by:** Abdul Mannan
