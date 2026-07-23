# Loan Eligibility Prediction ML Model

A machine learning project that explores the loan approval dataset from Kaggle to build predictive classification models. The project covers the complete machine learning workflow including exploratory data analysis, data preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation of multiple classification algorithms.

> **Note:** This project is intended for learning and experimentation with supervised machine learning techniques. It is not deployed as a web application.


---

## Overview-

Financial institutions process thousands of loan applications every day. Predicting whether a loan application should be approved is an important classification problem that helps reduce financial risk and improve decision making.

In this project, multiple machine learning algorithms are implemented and compared to predict the loan approval status based on applicant information.

---

## Dataset

* Source: Kaggle Loan Prediction Dataset
* Records: 614
* Features: 13
* Target Variable: `Loan_Status`

The dataset contains applicant information such as:

* Gender
* Marital Status
* Number of Dependents
* Education
* Self Employment Status
* Applicant Income
* Co-applicant Income
* Loan Amount
* Loan Term
* Credit History
* Property Area
* Loan Approval Status

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

* Dataset inspection
* Summary statistics
* Missing value analysis
* Distribution plots
* Boxplots for outlier detection
* Correlation heatmap
* Loan approval distribution
* Income vs Loan Amount visualization
* Gender-wise loan approval analysis

---

### 2. Data Preprocessing

* Missing numerical values filled using median
* Missing categorical values replaced with "missing"
* Label encoding of target variable
* Standardization of numerical features
* One-Hot Encoding for categorical variables
* Ordinal Encoding for tree-based models
* Train-Test Split (70:30)

---

### 3. Machine Learning Models

The following models were implemented and compared:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting Classifier

---

### 4. Hyperparameter Tuning

GridSearchCV was used to optimize model performance.

Models tuned include:

* Logistic Regression
* Random Forest
* Gradient Boosting

---

### 5. Model Evaluation

Performance was evaluated using:

* Accuracy
* ROC-AUC Score
* Precision
* Recall
* F1 Score
* Classification Report
* Confusion Matrix
* Permutation Feature Importance

---

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 84.86%   |
| Gradient Boosting   | 84.32%   |
| Random Forest       | 79.46%   |
| Decision Tree       | 77.29%   |

Among all models, Logistic Regression and Gradient Boosting achieved the best overall performance on the test dataset.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Repository Structure

```
.
├── Loan_Fraud_Detection.ipynb
└── README.md
```

---

## Future Improvements

* Experiment with XGBoost, CatBoost, and LightGBM
* Address class imbalance using SMOTE
* Perform more advanced feature engineering
* Use cross-validation for more robust evaluation
* Deploy the trained model as a Flask web application

---

## Learning Outcomes

Through this project, I gained hands-on experience with:

* Data cleaning and preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Classification Algorithms
* Hyperparameter Tuning
* Model Evaluation
* Machine Learning Pipelines using Scikit-learn

---

## Acknowledgements

* Kaggle for providing the Loan Prediction dataset.
* Scikit-learn documentation for machine learning implementation.

---

## Note

This project was originally developed as part of a first-semester machine learning assignment. The original collaborative repository and dataset are no longer available. This repository contains the reconstructed implementation and documentation based on the project work completed during the course. The dataset used is the publicly available Kaggle Loan Prediction dataset.

