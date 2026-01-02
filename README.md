# Placement Prediction using Machine Learning

## Problem Overview
This project aims to predict whether a student will be placed based on academic performance, skills, and training-related attributes using machine learning techniques.

---

## Dataset
The dataset contains student-level information such as:
- CGPA
- Internships and projects
- Aptitude and soft skill scores
- Placement training status
- School and higher secondary marks

The target variable represents the placement outcome (Placed / Not Placed).

---

## Approach
The project follows a structured machine learning pipeline:
- Exploratory Data Analysis (EDA) to understand trends and distributions
- Data cleaning and preprocessing, including encoding categorical variables
- Removal of non-informative identifier columns
- Training a Logistic Regression model for binary classification
- Model evaluation using accuracy and confusion matrix

---

## Results
The trained Logistic Regression model achieved an accuracy of **79.45%** on unseen test data, indicating that it learned meaningful patterns from the dataset.

---

## Observations
- CGPA shows a clear relationship with placement outcomes
- Placement is influenced by multiple factors, not a single feature
- Class distribution is slightly imbalanced but manageable

---

## Limitations
- Logistic Regression assumes linear relationships between features and the target
- Some real-world factors influencing placement are not captured in the dataset
- Accuracy alone may not fully represent model performance

---

## Future Scope
- Experiment with tree-based models such as Random Forest
- Apply feature scaling and selection
- Use additional evaluation metrics like precision and recall
