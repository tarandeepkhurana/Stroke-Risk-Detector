# Stroke Risk Detector

**Model Overview:** A machine learning model built using XGBoost Classifier to predict whether a person is at risk of stroke or not based on its symptoms.

**Dataset:** https://www.kaggle.com/datasets/mahatiratusher/stroke-risk-prediction-dataset-v2 (Contains 35000 instances with 16 features and 2 targets)

**Features Used:** age, gender, chest_pain, shortness_of_breath, irregular heartbeat, fatigue weakness, dizziness, etc.

**Tech stack:** 
- Python
- Scikit-learn
- Pandas
- NumPy
- Seaborn
- Matplotlib

**Model:** 
- Algorithm: XGBoost Classifier
- Evaluation Metrics:
    - Accuracy
    - Classification Report

**Results:**
- Accuracy: 98.75%
- Classification Report:
  
                 precision    recall  f1-score   support

           0       0.98      1.00      0.99      4467
           1       0.99      0.97      0.98      2533
