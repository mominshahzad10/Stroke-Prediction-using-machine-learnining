Stroke Prediction Using Machine Learning

Overview

This project presents a comprehensive study on predicting stroke likelihood using advanced machine learning techniques. Utilizing a Kaggle dataset of 20,000 patient records with 12 feature attributes, we employed LightGBM and XGBoost algorithms to accurately predict stroke occurrence. Our approach emphasizes the significance of key variables such as age, BMI, and glucose levels in stroke prediction.

Key Features

Data Analysis: Analyzed a Kaggle dataset comprising synthetic and real patient health records.
Machine Learning Models: Implemented LightGBM and XGBoost algorithms for stroke prediction.
Important Variables: Identified age, BMI, and glucose levels as critical factors in stroke likelihood.
Model Performance: Achieved an ROC AUC score of 0.888, demonstrating the models' effectiveness.
Methodology

Data Preprocessing: Addressed missing values, uneven data, and label encoding.
Exploratory Data Analysis (EDA): Employed various visualization techniques to understand data distribution and relationships.
Feature Engineering: Generated new features and utilized one-hot encoding for categorical variables.
Model Training and Evaluation: Trained models on upsampled data to handle class imbalance and evaluated using the ROC AUC score.
Results and Insights

Data Insights: EDA revealed crucial insights into stroke occurrences and feature distributions.
Model Performance: The baseline LightGBM model achieved a score of 0.84, which improved to 0.88 after feature engineering and hyperparameter optimization.
Discussion and Future Work

Effectiveness of ML in Healthcare: Demonstrated the potential of machine learning in early detection and intervention of strokes.
Future Directions: Suggested exploration of more advanced ML algorithms and ensemble methods, integration of additional relevant features, and leveraging AI for personalized stroke prediction models.
