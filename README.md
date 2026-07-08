#Loan Approval Prediction
##Overview
This project predicts whether a loan application will be approved or rejected using machine learning. The project includes the complete workflow, from data cleaning and visualization to model training and evaluation.
##Dataset
The dataset contains information about loan applicants, including:
Number of dependents
Education
Self-employed status
Annual income
Loan amount
Loan term
CIBIL score
Asset values
Loan status (target)
The original dataset and the cleaned dataset are both included in this repository.
##Project Workflow
Data loading
Data cleaning
Feature engineering
Exploratory Data Analysis (EDA)
Data visualization
Feature encoding
Train-test split
Model training
Model evaluation
Model comparison
##Feature Engineering
A new feature called total_assets was created by combining:
Residential assets
Commercial assets
Luxury assets
Bank assets
The original asset columns and the loan ID were removed after creating the new feature.
##Machine Learning Models
The following models were trained and compared:
Model
Accuracy
Logistic Regression
80.00%
Decision Tree
98.48%
Random Forest
97.54%
##Results
The Decision Tree achieved the highest accuracy on the test set. Random Forest also performed very well, while Logistic Regression served as a baseline model.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

##What I Learned
This project helped me understand the complete machine learning workflow, including data preprocessing, feature engineering, exploratory data analysis, training classification models, evaluating model performance, and comparing different algorithms.
