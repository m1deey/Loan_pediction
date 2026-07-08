## Loan Approval Prediction

## Overview

This project uses machine learning to predict whether a loan application will be approved or rejected. The project covers the complete machine learning workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison.

---

## Dataset

The dataset contains information about loan applicants, including:

- Number of dependents
- Education
- Self-employed status
- Annual income
- Loan amount
- Loan term
- CIBIL score
- Residential assets
- Commercial assets
- Luxury assets
- Bank assets
- Loan approval status (Target)

Both the original dataset and the cleaned dataset are included in this repository.

---

## Project Workflow

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Feature Encoding
- Train-Test Split
- Model Training
- Model Evaluation
- Model Comparison

---

## Feature Engineering

A new feature called **total_assets** was created by combining:

- Residential Assets
- Commercial Assets
- Luxury Assets
- Bank Assets

The original asset columns and the loan ID column were removed after creating the new feature.

---

## Machine Learning Models

The following models were trained and compared:

| Model | Accuracy |
|-------|---------:|
| Logistic Regression | 80.00% |
| Decision Tree | 98.48% |
| Random Forest | 97.54% |

---

## Results

- Logistic Regression provided a good baseline model.
- Decision Tree achieved the highest accuracy on the test dataset.
- Random Forest also performed very well and produced results close to the Decision Tree.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---


## What I Learned

Through this project, I learned how to:

- Clean and prepare real-world data.
- Perform exploratory data analysis using different visualizations.
- Engineer new features to improve the dataset.
- Encode categorical variables for machine learning.
- Split data into training and testing sets.
- Train and evaluate multiple machine learning models.
- Compare different algorithms using performance metrics such as accuracy, precision, recall, and F1-score.

---

## Conclusion

This project demonstrates a complete machine learning workflow, from raw data to model evaluation. Comparing multiple algorithms showed that tree-based models performed significantly better than Logistic Regression on this dataset. This project also strengthened my understanding of data preprocessing, exploratory data analysis, feature engineering, and supervised machine learning.
