# CSI-4130-5130-Artificial-Intelligence
Titanic - Machine Learning from Disaster

# Titanic Survival Prediction using Machine Learning Course Project  
Author: Ayana Edwards


---

# Project Description

This project investigates how machine learning can be used to analyze historical passenger data and predict survival outcomes during the Titanic disaster. The goal is to build an artificial intelligence model that learns patterns from known passenger records and uses those patterns to predict survival for other passengers.

The project demonstrates the full machine learning pipeline including data exploration, preprocessing, model training, and prediction generation. The implementation uses Python and common data science tools to construct a predictive model capable of identifying factors that influenced survival during the disaster.

---

# Challenge Objective

The Titanic disaster of 1912 remains one of the most studied maritime accidents in history. While the event resulted in a large number of fatalities, historical records indicate that survival was influenced by several passenger characteristics.

The objective of this challenge is to build a predictive model capable of answering the following question:

**Which types of passengers were more likely to survive the Titanic disaster?**

Using passenger data such as age, gender, ticket class, and travel information, the model attempts to identify patterns associated with survival outcomes. These patterns are then applied to new passenger records to estimate survival probability.

## Problem Type

This is a **binary classification** problem.

- `0` = Did Not Survive
- `1` = Survived

Because the target variable is categorical, a classification algorithm was used instead of regression.

## Dataset Files

This project used three Kaggle competition files:

- `train.csv` – labeled dataset used for training and validation
- `test.csv` – unlabeled dataset used for final predictions
- `gender_submission.csv` – example submission format provided by Kaggle
  
# Dataset

The dataset used in this project is obtained from the Kaggle Titanic Machine Learning competition. The competition provides two primary datasets.

## Workflow

The notebook was expanded into a more complete machine learning pipeline:

1. Load and inspect the Titanic dataset  
2. Clean missing values  
3. Encode categorical variables  
4. Perform feature engineering  
5. Define features and target  
6. Split training and validation data  
7. Train a baseline Random Forest model  
8. Evaluate model performance  
9. Compare improved models  
10. Generate final predictions and Kaggle submissions  

### Training Dataset

The training dataset contains records for **891 passengers**. Each record includes passenger characteristics and a labeled survival outcome. These labeled examples allow the machine learning model to learn relationships between passenger attributes and survival results.

Example features include:

- Passenger class
- Gender
- Age
- Family relationships aboard the ship
- Ticket fare
- Port of embarkation

## Data Preprocessing

The preprocessing stage included:

- Handling missing values in `Age` and `Embarked`
- Dropping `Cabin` due to excessive missing data
- Encoding `Sex` and `Embarked` into numeric values
- Preparing the dataset for model training

## Feature Engineering

Additional preparation steps were added to improve model readiness, including:

- creating structured model inputs
- improving consistency in the dataset
- selecting the most relevant predictors for survival classification

## Model Used

The main model used in this project was a **Random Forest Classifier**.

Random Forest was selected because:

- the problem is a binary classification task
- the dataset is structured tabular data
- the model handles mixed feature types well
- ensemble learning helps reduce overfitting compared to a single decision tree

## Evaluation Metrics

The improved model evaluation stage included:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

### Validation Results

- **Accuracy:** 81.56%
- **Precision:** 78.13%
- **Recall:** 72.46%
- **F1 Score:** 75.19%

These metrics provided a more complete view of model performance than accuracy alone.

## Kaggle Competition Results

Two competition submissions were generated.

- **First submission:** 0.75358
- **Best submission:** 0.76555

The improved notebook workflow strengthened evaluation and retraining, while the Kaggle score continued to depend only on the final submission format and predicted survival values.

## Key Findings

- Survival was strongly influenced by demographic and class-related patterns
- The Random Forest model performed well as a baseline classifier
- Adding validation and evaluation improved the modeling workflow
- The model performed better at identifying non-survivors than survivors
- Internal validation metrics gave a clearer understanding of model strengths and weaknesses

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Kaggle Notebook Environment

## Files in This Repository

- `Titanic 041326.ipynb` – main project notebook
- `README.md` – project overview and results
- `submission.csv` – final Kaggle submission file (if included)

## Conclusion

This project demonstrates how machine learning can be used to solve a real-world classification problem using historical passenger data. By improving preprocessing, evaluation, and retraining steps, the workflow became more systematic and the model became easier to assess and refine.

## Author

Ayana Edwards
