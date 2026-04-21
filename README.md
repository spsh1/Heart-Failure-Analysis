# Heart Disease Prediction Machine Learning Project

## Overview
This project presents an end-to-end machine learning pipeline to predict the likelihood of heart disease based on patient health and clinical attributes. The workflow includes data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and model persistence.

Multiple supervised learning algorithms are implemented and compared to determine the best-performing model.

---

## Objective
To build a machine learning model capable of accurately classifying whether a patient is at risk of heart disease using structured medical data.

---

## Dataset
The dataset consists of patient health records with various medical attributes.

### Target Variable
- HeartDisease (Binary Classification)
  - 0: No disease
  - 1: Disease present

### Features
- Age
- Resting Blood Pressure
- Cholesterol
- Maximum Heart Rate
- Exercise-induced Angina
- Other clinical and demographic attributes

---

## Project Workflow

### 1. Data Preprocessing
- Handling missing values using mean, median, and mode imputation
- Encoding categorical variables using One-Hot Encoding
- Feature scaling using StandardScaler
- Train-test split with stratification

---

### 2. Exploratory Data Analysis (EDA)
- Correlation heatmaps
- Distribution analysis of numerical features
- Relationship analysis between features and target variable
- Class distribution analysis

---

### 3. Feature Engineering
- One-hot encoding of categorical variables
- Standardization of numerical features
- Removal of irrelevant or redundant columns

---

### 4. Machine Learning Models Implemented
The following models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Gradient Boosting Classifier
- Multi-Layer Perceptron (MLP Neural Network)

---

## Model Evaluation Metrics
All models were evaluated using:

- Accuracy Score
- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC Curve
- Precision-Recall Curve

---

## Best Performing Model
The Random Forest Classifier achieved the best overall performance in terms of accuracy and generalization ability on the test dataset.

---

## Results Summary
- Ensemble methods outperformed most individual classifiers
- Tree-based models showed strong predictive capability
- Consistent evaluation metrics ensured fair comparison
- Model performance indicates strong classification ability on the dataset

---

## Model Saving
All trained models were saved using Joblib for reuse and deployment.

Saved models include:
- Random Forest Classifier
- Decision Tree Classifier
- SVM Model
- KNN Model
- Gradient Boosting Model
- MLP Model

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Graphviz
- Joblib

---

## Installation

```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
pip install -r requirements.txt
