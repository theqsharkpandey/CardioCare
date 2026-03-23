Cardiovascular Risk Prediction using Deep Neural Networks
Overview

This project focuses on predicting cardiovascular (heart) disease using multiple machine learning and deep learning models. The objective is to compare different algorithms and identify the most accurate and reliable model for early diagnosis.

The system uses clinical and medical attributes such as age, cholesterol, and blood pressure to determine the likelihood of heart disease.

Highlights
Implemented and compared 15+ machine learning and deep learning models
Conducted detailed performance evaluation and model comparison
Presented this work at ICCCNT 2025 (IEEE), IIT Indore
Features
End-to-end machine learning pipeline
Data preprocessing and feature selection
Model training and evaluation
Performance comparison across multiple algorithms
Analysis of overfitting and generalization
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

The project uses the UCI Heart Disease Dataset (1988), which consists of four databases:

Cleveland
Hungary
Switzerland
Long Beach V

The dataset contains 76 attributes, with 14 commonly used features in most experiments.

The target variable indicates the presence of heart disease:

0 → No disease
1 → Disease present
Tech Stack
Python
NumPy
Pandas
Scikit-learn
TensorFlow / Keras
Matplotlib
Installation
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
Usage

Run the Jupyter Notebook:

jupyter notebook

Open the file:

Comparative_Analysis_of_Deep_Neural_Networks_for_Cardiovascular_Risk_Prediction.ipynb
Results

Several tree-based models showed signs of overfitting with very high accuracy.

Deep learning models demonstrated better generalization in some cases.

The comparative analysis helped identify more stable and reliable models for prediction.

Research Contribution

This work was presented at the Sixteenth International Conference on Computing, Communication and Networking Technologies (ICCCNT 2025), held at IIT Indore in association with IEEE.

[View Certificate](https://drive.google.com/file/d/1ryP_b_AcexCMTMX885WkzTTdod3XBJcb/view)

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
Author

Kushagra Pandey
Portfolio: https://kp3000.vercel.app/

GitHub: https://github.com/theqsharkpandey

License

This project is licensed under the MIT License.
