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

---

# Dataset

The dataset used in this project is obtained from the Kaggle Titanic Machine Learning competition. The competition provides two primary datasets.

### Training Dataset

The training dataset contains records for **891 passengers**. Each record includes passenger characteristics and a labeled survival outcome. These labeled examples allow the machine learning model to learn relationships between passenger attributes and survival results.

Example features include:

- Passenger class
- Gender
- Age
- Family relationships aboard the ship
- Ticket fare
- Port of embarkation

### Test Dataset

The test dataset contains records for **418 passengers**. These records contain the same passenger attributes but do not include the survival outcome. The trained model must predict whether each passenger survived.

---

# Prediction Task

The prediction task is formulated as a binary classification problem. For every passenger in the test dataset, the model must output one of two possible values: 
0 = passenger did not survive 
1 = passenger survived

---


Each row represents the model's predicted survival outcome for a passenger in the test dataset.

---

# Model Evaluation

Predictions are evaluated using **classification accuracy**, which measures how often the model correctly predicts survival outcomes.

Accuracy represents the proportion of correct predictions made by the model compared to the total number of predictions.

Higher accuracy indicates that the model successfully captured meaningful patterns in the passenger data.

---

# Minimum Performance Requirement

To demonstrate that the machine learning model performs effectively, the project requires achieving an accuracy score **greater than 70%**.

Models trained on the Titanic dataset commonly reach accuracy levels between: 70%-85%


## Current Progress

✔ Data exploration and visualization
✔ Data preprocessing and feature preparation

## Future Work
✔ Model training using Random Forest
✔ Prediction generation for test passengers
✔ Submission file creation
✔ Presentaion Slides
✔ Final Report

## Citations and Acknowledgements

Titanic Dataset – Kaggle Machine Learning Competition  
https://www.kaggle.com/competitions/titanic

Scikit-Learn Machine Learning Library  
https://scikit-learn.org

Pandas Data Analysis Library  
https://pandas.pydata.org



