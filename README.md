# Machine-Learning-Model-for-Titanic-Dataset-
The objective is to perform Exploratory Data Analysis (EDA) to better understand the dataset, preprocess the data (handle missing values, encode categorical features, etc.), and build a machine learning model to predict the survival of passengers. Different machine learning algorithms, such as Logistic Regression, Random Forest, and Support vector.
# Titanic Survival Prediction: Machine Learning Model

## Project Overview

This project applies machine learning to predict the survival of passengers aboard the Titanic based on various features such as age, class, gender, and more. The goal is to develop a model that can predict whether a passenger survived or not based on these attributes.

### **Dataset Overview:**
- **Train Dataset (`train.csv`)**: This dataset contains information about passengers who were on the Titanic, including whether they survived or not.
- **Test Dataset (`test.csv`)**: This dataset is used to test the machine learning model's prediction on unseen data.

## Objectives
- Preprocess the Titanic dataset for analysis.
- Build a machine learning model to predict the survival of passengers.
- Evaluate the performance of the model using various metrics.
Model Evaluation
Accuracy: Measures the percentage of correct predictions made by the model.

Confusion Matrix: Shows the number of true positives, false positives, true negatives, and false negatives.

ROC Curve: A graph showing the performance of the classification model.

Results
Model 1: Logistic Regression

Accuracy: 79%

Precision: 80%

Recall: 77%

Model 2: Random Forest

Accuracy: 81%

Precision: 83%

Recall: 79%

Technologies Used:
Python: Programming language.

Pandas: Data manipulation.

NumPy: Numerical computation.

Scikit-learn: Machine learning algorithms and tools.

Matplotlib & Seaborn: Data visualization.

Titanic-ML-Project/
│
├── data/                     # Titanic dataset (train.csv, test.csv)
│   ├── train.csv             # Training dataset
│   └── test.csv              # Test dataset
│
├── notebooks/                # Jupyter notebooks for analysis and modeling
│   └── titanic_model.ipynb   # Titanic model training and evaluation notebook
│
├── requirements.txt          # Project dependencies (libraries)
├── model/                    # Saved machine learning models (e.g., .pkl files)
├── README.md                 # Project overview and documentation
└── results/                  # Evaluation results (e.g., accuracy, confusion matrix)
