# Fraud Detection

## Overview

This project focuses on detecting fraudulent transactions using **machine learning techniques**. By analyzing transaction patterns and applying predictive models, the system aims to distinguish between legitimate and fraudulent activities to help prevent financial losses.

---

## Features

* **Data Loading & Exploration**: Import and analyze transaction datasets to understand feature distribution and detect anomalies.
* **Data Preprocessing**: Handle missing values, encode categorical variables, and scale numerical features.
* **Exploratory Data Analysis (EDA)**: Visualize trends, correlations, and class imbalances using **Matplotlib** and **Seaborn**.
* **Model Training**: Implement supervised learning algorithms for fraud detection.
* **Evaluation**: Assess model performance using accuracy, precision, recall, F1-score, and ROC-AUC metrics.

---

## Dataset

* **File**: `AIML Dataset.csv`
https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset?resource=download
* Contains transaction records with features such as:

  * `amount`, `oldbalanceOrg`, `newbalanceOrig`, `oldbalanceDest`, `newbalanceDest`, etc.
  * Target variable: `isFraud` (1 = Fraudulent, 0 = Legitimate)

---

## Technologies Used

* **Data Processing**: Pandas, NumPy
* **Visualization**: Matplotlib, Seaborn
* **Machine Learning**: Scikit-learn,  XGBoost
* **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, ROC-AUC

---

## Workflow

1. **Load Data** → Read and inspect dataset structure.
2. **EDA** → Explore data distribution, detect outliers, and analyze class imbalance.
3. **Preprocessing** → Scale features, encode categories, and handle missing values.
4. **Modeling** → Train and compare multiple ML models.
5. **Evaluation** → Select the best model based on key performance metrics.


