# Healthcare Risk Prediction System using Machine Learning

A machine learning project that predicts the likelihood of three major chronic health conditions—**Diabetes**, **Hypertension**, and **Stroke**—using supervised learning algorithms. The project compares multiple classification models to evaluate their effectiveness in predicting healthcare risks from patient health indicators.

---

## Overview

Early identification of chronic diseases can significantly improve patient outcomes and support preventive healthcare. This project applies supervised machine learning techniques to classify patients based on their risk of developing:

* Diabetes
* Hypertension
* Stroke

Several classification algorithms were trained and evaluated using the same dataset to compare predictive performance across different healthcare prediction tasks.

---

## Dataset

The project uses a healthcare dataset containing:

* **70,692 patient records**
* **18 health-related features**
* **3 binary target variables**

  * Diabetes
  * Hypertension
  * Stroke

### Features include

* Age
* Sex
* BMI
* High Cholesterol
* Cholesterol Check
* Smoking Status
* Heart Disease
* Physical Activity
* Fruit Consumption
* Vegetable Consumption
* Heavy Alcohol Consumption
* General Health
* Difficulty Walking
* and other lifestyle and medical indicators.

---

## Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Selection
        │
        ▼
Feature Scaling
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Performance Comparison
```

---

## Data Preprocessing

The dataset was prepared through several preprocessing steps before training:

* Removed missing values
* Checked duplicate and unique records
* Dropped unnecessary features after exploratory analysis
* Standardized numerical features using **StandardScaler**
* Prepared separate target variables for each prediction task

---

## Exploratory Data Analysis

The project includes visual exploration of the dataset using:

* Bar charts
* Correlation heatmaps
* Feature distribution analysis

These visualizations were used to understand feature relationships and guide preprocessing decisions.

---

## Machine Learning Models

Five supervised classification algorithms were implemented and compared:

* Logistic Regression
* Gaussian Naive Bayes
* Bernoulli Naive Bayes
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier

Each model was trained independently for:

* Stroke Prediction
* Hypertension Prediction
* Diabetes Prediction

---

## Model Evaluation

The models were evaluated using standard classification metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC Curve
* Area Under the ROC Curve (AUC)

This comparative evaluation helps identify which algorithms perform better for different healthcare prediction tasks.

---

## Results

The experimental results demonstrate that traditional supervised learning algorithms can effectively predict multiple chronic diseases using structured healthcare data.

Key observations include:

* Logistic Regression achieved consistently strong performance across prediction tasks.
* K-Nearest Neighbors and Decision Tree achieved high classification accuracy in several experiments.
* Naive Bayes classifiers provided competitive baseline performance with lower computational complexity.
* Model performance varied depending on the target disease, highlighting the importance of algorithm selection for different healthcare applications.

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


## Future Improvements

Planned enhancements include:

* Hyperparameter optimization
* Cross-validation
* Feature importance analysis
* Ensemble learning methods
* XGBoost and Random Forest implementation
* Deep learning approaches
* Model deployment with a web interface

---


## Author

**Najifa Tasnim**

Machine Learning • AI Applications • Data Analytics
