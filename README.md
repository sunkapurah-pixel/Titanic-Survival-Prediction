# Titanic Survival Prediction

## Overview

This project aims to predict whether a passenger survived the Titanic disaster using Machine Learning techniques. The prediction is based on passenger information such as age, gender, passenger class, fare, family size, and other attributes.

The project includes data preprocessing, feature engineering, model training, evaluation, and model explainability.

## Dataset

Dataset Source:
https://www.kaggle.com/datasets/bhanupratapbiswas/titanic-survival-datasets

The dataset contains information about Titanic passengers, including demographic and travel details.

### Features

* Passenger Class (Pclass)
* Name
* Sex
* Age
* Siblings/Spouses Aboard (SibSp)
* Parents/Children Aboard (Parch)
* Fare
* Cabin
* Embarked

### Target Variable

* Survived (0 = No, 1 = Yes)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook

## Project Workflow

### 1. Data Collection

* Loaded the Titanic dataset using Pandas.

### 2. Exploratory Data Analysis (EDA)

* Dataset inspection
* Missing value analysis
* Survival distribution analysis
* Feature correlation analysis

### 3. Feature Engineering

The following new features were created:

* Title Extraction from passenger names
* Family Size Calculation
* Cabin Presence Indicator

### 4. Data Preprocessing

* Handled missing values in Age, Fare, and Embarked columns.
* Encoded categorical variables into numerical values.

### 5. Model Building

A Random Forest Classifier was implemented to predict passenger survival.

### 6. Model Evaluation

The model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* Classification Report

### 7. Model Explainability

Feature importance analysis was performed to identify the most influential features affecting survival.

### 8. Model Saving

The trained model was saved using Joblib for future predictions.

## Results

The model achieved good classification performance with high prediction accuracy on the test dataset.



## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Deployment using Flask or Streamlit

## Author

Hanumakshi
