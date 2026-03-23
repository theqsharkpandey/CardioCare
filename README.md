Cardiovascular Risk Prediction using Deep Neural Networks
Overview

This project focuses on predicting cardiovascular (heart) disease using multiple machine learning and deep learning models. The objective is to compare different algorithms and identify the most accurate and reliable model for early diagnosis.

The dataset consists of various medical attributes such as age, cholesterol, blood pressure, and other clinical parameters used to predict the presence of heart disease.

Features
Implementation of 15+ machine learning and deep learning models
Comparative analysis of model performance
Evaluation using accuracy, precision, recall, and confusion matrix
Data preprocessing and feature selection
Analysis and handling of overfitting
Models Used
Machine Learning Models
Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Naive Bayes
Extra Trees Classifier
Bagging Classifier
XGBoost
LightGBM
Deep Learning Models
Artificial Neural Networks (ANN)
Deep Neural Networks (DNN)
Dataset
Source: UCI Heart Disease Dataset (1988)
Databases included:
Cleveland
Hungary
Switzerland
Long Beach V
Total attributes: 76
Commonly used features: 14
Target Variable
0 → No heart disease
1 → Presence of heart disease
Tech Stack
Language: Python
Libraries:
NumPy
Pandas
Scikit-learn
TensorFlow / Keras
Matplotlib / Seaborn
Installation
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
Usage
jupyter notebook

Open the notebook:

Comparative_Analysis_of_Deep_Neural_Networks_for_Cardiovascular_Risk_Prediction.ipynb
Results
Several tree-based models showed overfitting (accuracy close to 1.0)
Deep learning models demonstrated better generalization in some cases
Comparative evaluation helped identify more stable models
Challenges
Overfitting in ensemble and tree-based models
Data imbalance
Feature selection complexity
Future Work
Use larger and more recent datasets
Apply cross-validation techniques
Perform advanced hyperparameter tuning
Deploy as a web application
Build a real-time prediction system
Contributing

Contributions are welcome.

git checkout -b feature-name
git commit -m "Add feature"
git push origin feature-name
License

This project is licensed under the MIT License.
