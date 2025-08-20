# Detection-of-Diabetic-Female-Patients-
Detection of Diabetic Female Patients using Pima Indians Diabetes Dataset

# Pima Indian Diabetes Prediction

## Project Description
This project involves predicting diabetes in Pima Indian patients using multiple machine learning models. Various classification algorithms are applied and optimized through hyperparameter tuning to achieve the best model accuracy. The goal is to compare models and find the most effective approach for accurate diabetes prediction.

## Dataset
The dataset used is the Pima Indian Diabetes dataset, which contains diagnostic measurements to predict diabetes presence in female patients of Pima Indian heritage.The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.
Link to Dataset : https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database 


## Models Used and Performance

| Model                       | Training Accuracy           | Validation Accuracy         | Notes                        |
|-----------------------------|----------------------------|-----------------------------|------------------------------|
| K-Nearest Neighbors (KNN)   | 80.46%                     | 66.88%                      | Baseline without tuning       |
| KNN (After Hyperparameter Tuning with GridSearch CV) | 79.48% | 72.73%                      | Improved validation accuracy   |
| Decision Tree               | 100.00%                    | 68.18%                      | Baseline without tuning       |
| Decision Tree (After Hyperparameter Tuning) | 81.76%          | 74.68%                      | Reduced overfitting, better generalization |
| Random Forest Classifier    | 100.00%                    | 73.38%                      | Baseline without tuning       |
| Random Forest (After Hyperparameter Tuning) | 97.72%          | 75.32%                      | Strong validation performance |
| Logistic Regression         | 77.85%                     | 76.62%                      | Consistent performance        |


