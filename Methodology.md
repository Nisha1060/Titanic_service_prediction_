# Methodology
## 1. Refined Research Question
Can passenger characteristics and engineered family-related features predict Titanic survival using Logistic Regression and Random Forest?
## 2. Dataset Description
The Kaggle Titanic dataset contains **891 rows and 12 columns**, with `Survived` as the target and passenger characteristics as predictors.
## 3. Data Cleaning Plan
Duplicates will be removed, identifier-like columns will be dropped, and missing `Age` and `Embarked` values will be handled using a preprocessing pipeline.
## 4. Feature Engineering Plan
New features such as **FamilySize, IsAlone, FarePerPerson, and Title** will be created from existing passenger information.
## 5. Models
The experiment will compare **Logistic Regression** as a baseline classifier with **Random Forest** as a nonlinear ensemble classifier.
## 6. Evaluation Metrics
Both models will be evaluated on the same test set using **Accuracy, Precision, Recall, and F1-score**.
## 7. Reproducibility
A stratified **80/20 train-test split**, `random_state=42`, and scikit-learn preprocessing pipelines will be used for reproducible results.
