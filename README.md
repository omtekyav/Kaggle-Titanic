# Kaggle-Titanic Project
![RMS_Titanic_3](https://github.com/user-attachments/assets/9bf4515c-2bc4-4398-ac5a-11f94ba931b6)

 In this repository Titanic project will be demonstrated and the data set is acquired from https://www.kaggle.com/competitions/titanic
 ## Workflow
 Overview

This project analyzes passenger survival on the Titanic using machine learning. The workflow includes data preprocessing, feature engineering, and model training with hyperparameter tuning to achieve optimal performance.

## 📢 Note:
This section provides a surface-level explanation to help understand the general concept of the project. For a detailed understanding of the code execution and the project's full workflow, please refer to the titanic_kaggle.ipynb notebook associated with the commit message "final classification with train/test accuracies added" in the repository.
![image](https://github.com/user-attachments/assets/31f4662f-2909-455d-a6cc-0b7b43fd3686)



# Workflow

## 1. Data Preparation

Train and test dataset indices were extracted.

Combined training and test datasets.

## 2. Data Preprocessing

Handling Missing Values

Age Imputation: Instead of using the median of the entire dataset, missing age values were filled based on median values per passenger class.

Fare Imputation: The missing fare value was replaced using the median of passengers with the same Pclass and Embarked values.

Confirmed that all missing values were filled.

## 3. Feature Engineering

Applied Label Encoding to categorical features.

Feature Scaling using MinMaxScaler.

## 4. Model Training

Split dataset into training and test sets.

Random Forest Classifier as the baseline model.

## 5. Hyperparameter Tuning

Used RandomizedSearchCV to optimize model performance.

Final Model Performance:

Train Accuracy: 0.8286

Test Accuracy: 0.8212

Conclusion

Through data preprocessing, feature engineering, and hyperparameter tuning, the model achieved an accuracy of 82.1% on the test set, improving from the baseline Random Forest model. Further enhancements could be made by experimenting with different models or additional feature extraction techniques.
 

 
