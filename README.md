# Pluto_Proj2

# Heart Disease Prediction using Machine Learning

## Project Overview

This project builds and evaluates multiple machine learning models to predict the likelihood of heart disease using patient health data. The project follows a complete machine learning workflow including preprocessing, feature analysis, model training, evaluation, and comparison.

---

## Objective

To predict whether a patient has heart disease using machine learning algorithms and identify the best-performing model through evaluation metrics.

---

## Dataset

Dataset: Heart Disease Prediction Dataset

Features include:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Blood Sugar
* ECG Results
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression
* Slope
* Number of Major Vessels
* Thalassemia

Target:

* 0 → No Heart Disease
* 1 → Heart Disease

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* GitHub

---

## Project Workflow

### 1. Data Loading & Exploration

* Loaded dataset into Pandas
* Checked shape, data types, and statistics
* Verified missing values

### 2. Data Preprocessing

* Feature and target separation
* Train-test split (80/20)

### 3. Feature Engineering

* Correlation analysis using heatmap

### 4. Model Training

Three machine learning models were trained:

* Logistic Regression
* Random Forest Classifier
* K Nearest Neighbors (KNN)

### 5. Model Evaluation

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Model Comparison

| Model               | Accuracy | Precision | Recall | F1 Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 79.5%    | 75.6%     | 87.4%  | 81.1%    |
| Random Forest       | 98.5%    | 100.0%    | 97.1%  | 98.5%    |
| KNN                 | 73.2%    | 73.1%     | 73.8%  | 73.4%    |

---

## Best Model

🏆 Random Forest Classifier

Reason:

* Highest Accuracy
* Perfect Precision
* Excellent Recall
* Highest F1 Score

---

## Results

The Random Forest model achieved outstanding performance in predicting heart disease and significantly outperformed Logistic Regression and KNN.

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Deployment using Streamlit
* Real-time prediction system

---

## Author

Shlok Patel
