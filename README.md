# Heart Disease Prediction
A machine learning model that predicts heart disease presence using patient data with a tuned Random Forest Classifier.

Dataset:
  
    Source: UCI Heart Disease Dataset
  
  Format: CSV
  
  Features: 13 attributes (age, sex, chest pain type, etc.)
  
  Target: Presence of heart disease (1) or not (0)

Model Used:
  
  Algorithm: Random Forest Classifier
  
  Tuning: GridSearchCV for hyperparameter optimization
  
  Scaler: StandardScaler for normalization

Model Performance:
  
  Metric	Score
  
  Accuracy	0.8641
  
  Precision	0.8868
  
  Recall	0.8785
  
  F1-Score	0.8826

  Confusion Matrix
             Predicted
           0     1
Actual 0  [65    12]
       1  [13    94]

Dependencies:
  
  pandas
  
  numpy
  
  matplotlib
  
  seaborn
  
  scikit-learn
