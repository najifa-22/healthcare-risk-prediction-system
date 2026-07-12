# Healthcare Risk Prediction System using Machine Learning

A machine learning framework for predicting **Diabetes**, **Hypertension**, and **Stroke** using standardized disease-specific classification pipelines. Multiple supervised learning algorithms are evaluated through a comprehensive framework incorporating accuracy, precision, recall, F1-score, confusion matrices, and ROC curves.



## Overview

Early identification of chronic diseases can significantly improve patient outcomes and support preventive healthcare. This project applies supervised machine learning techniques to classify patients based on their risk of developing:

* Diabetes
* Hypertension
* Stroke

Several classification algorithms were trained and evaluated using the same dataset to compare predictive performance across different healthcare prediction tasks.



## Dataset

The project uses a healthcare dataset containing:

* **70,692 patient records**
* **18 health-related features**
* **Three binary prediction tasks:**
  
  * Stroke
  * Hypertension
  * Diabetes
  

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
Feature Analysis
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



## Data Preprocessing

The dataset was prepared through several preprocessing steps before model training:

- Checked missing values, duplicate records, and data consistency
- Created independent target variables for each disease prediction task
- Standardized numerical features using **StandardScaler**
- Prepared disease-specific training and testing datasets



## Exploratory Data Analysis

The project includes visual exploration of the dataset using:

* Bar charts
* Correlation heatmaps
* Feature distribution analysis

These visualizations were used to understand feature relationships and support data understanding and model development.


### Target Variable Distribution

The distribution of the three target variables was analyzed to examine class balance across the prediction tasks.

![Target Distribution](images/1.%20Distribution%20of%20Target%20Variables.png)


### Feature Correlation Heatmap

A correlation heatmap was used to examine relationships between the health-related features and support data understanding prior to model development.

![Correlation Heatmap](images/4.%20Feature%20Correlation%20Heatmap.png)



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



## Model Evaluation

The models were evaluated using standard classification metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC Curve
* Area Under the ROC Curve (AUC)

Performance was compared across models to analyze the trade-offs between overall predictive accuracy and disease detection capability for each prediction task.

### Model Accuracy Comparison

The figures below summarize the accuracy achieved by each classifier for Stroke, Hypertension, and Diabetes prediction.

| Stroke | Hypertension | Diabetes |
|--------|--------------|----------|
| ![](images/5.%20Stroke%20Accuracy%20Comparison.png) | ![](images/6.%20Hypertension%20Accuracy%20Comparison.png) | ![](images/7.%20Diabetes%20Accuracy%20Comparison.png) |



## Results

The experimental results demonstrate that traditional supervised learning algorithms can effectively predict multiple chronic diseases using structured healthcare data.

Key observations include:

* Logistic Regression achieved consistently strong performance across prediction tasks.
* K-Nearest Neighbors and Decision Tree achieved high classification accuracy in several experiments.
* Naive Bayes classifiers provided competitive baseline performance with lower computational complexity.
* Model performance varied depending on the target disease, highlighting the importance of algorithm selection for different healthcare applications.



## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook



## Future Improvements

Planned enhancements include:

* Cross-validation
* Feature importance analysis
* Ensemble learning methods
* XGBoost and Random Forest implementation
* Deep learning approaches
* Model deployment with a web interface



## Author

**Najifa Tasnim**

Machine Learning • AI Applications • Data Analytics
