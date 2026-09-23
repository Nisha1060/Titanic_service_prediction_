# Titanic_service_prediction_
# Titanic Survival Classification
This project investigates whether passenger characteristics and engineered family-related features can be used to predict survival on the Titanic.
## Research Question
Can passenger characteristics and engineered family-related features be used to predict Titanic survival, and how do **Logistic Regression** and **Random Forest** compare in terms of classification performance?
## Project Overview
The Titanic dataset contains information about passengers, including age, gender, passenger class, fare, and family-related information.
In this project, the data is cleaned and relevant features are engineered to prepare the dataset for machine learning. Two classification models are then trained and evaluated:
* Logistic Regression
* Random Forest
The performance of both models is compared using standard classification metrics.
## Project Files
```text
Titanic-Survival-Classification/
│
├── data/
│   └── titanic.csv
│
├── literature_review.md
├── methodology.md
├── experiment.ipynb
└── README.md
```
### File Descriptions
* **`data/titanic.csv`** — Titanic passenger dataset used for the experiment.
* **`literature_review.md`** — Literature review of four related sources.
* **`methodology.md`** — Research question, dataset description, data cleaning plan, feature engineering, models, and evaluation methodology.
* **`experiment.ipynb`** — Complete experiment including data preprocessing, feature engineering, model training, evaluation, and findings.
## Features
The project uses passenger characteristics and engineered family-related features, such as:
* Passenger class
* Sex
* Age
* Fare
* Number of siblings/spouses
* Number of parents/children
* Family size
* Other family-related information
## Machine Learning Models
### 1. Logistic Regression
Logistic Regression is used as a baseline classification model for predicting whether a passenger survived.
### 2. Random Forest
Random Forest is us
