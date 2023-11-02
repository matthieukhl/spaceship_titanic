# Spaceship Titanic Passenger Transport Prediction

## Overview
This project focuses on predicting whether passengers aboard the Spaceship Titanic were transported to another dimension. It involves an extensive machine learning pipeline from data preprocessing to model evaluation.

## Data Source
The dataset used can be found on [Kaggle](https://www.kaggle.com/competitions/spaceship-titanic/data?select=train.csv).

## Steps
1. **Data Exploration**: Initial analysis to understand the dataset's features and structure.
2. **Data Preprocessing**: Involved handling missing values, feature extraction from the 'Cabin' column, and encoding categorical variables.
3. **Feature Scaling**: Standardization of numerical features for model compatibility.
4. **Model Training**: Trained Random Forest and Gradient Boosting Classifiers.
5. **Model Evaluation**: Evaluated models using accuracy as the primary metric, achieving approximately 79.7% accuracy with the Gradient Boosting Classifier.
6. **Fine-Tuning**: Attempted fine-tuning of the Random Forest Classifier using GridSearchCV.

## Conclusion
The project successfully applies machine learning techniques to predict passenger transport, with promising results. Future work could explore further model optimization or additional feature engineering.
