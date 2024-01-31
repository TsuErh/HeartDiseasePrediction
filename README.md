# HeartDiseasePrediction

Dataset
  > From Kaggle "Heart Attack Analysis & Prediction Dataset" (https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)
  > Dataset: 13 columns/features and 1 target
  > Target: leass chance of heart attack (0) and more chance of heart attack (1)

Feature Detail
  > Age: age of patient (numerical data)
  > Sex: sex of the patient (categorical data)
  > exang: exercise induced angina, yes <1> and no <0> (categorical data) 
  > ca: number of major vessels <0 - 3> (categorical data)
  > cp: chest pain type (categorical data)
    - Value 1: typical angina
    - Value 2: atypical angina
    - Value 3: non-anginal pain
    - Value 4: asymptomatic 
  > trtbps: resting blood pressure (numerical data)  
  > chol: cholestoral in mg/dl fetched via BMI sensor (numerical data)
  > fbs: fasting blood sugar, > 120 mg/dl <1>, otherwise <0> (categorical data)
  > rest_ecg: resting electrocardiographic results (categorical data)
    - Value 0: normal
    - Value 1: having ST-T wave abnormality
    - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
  > thalach: maximum heart rate achieved (numberical data)


Approach
  > EDA for numerical and categorical dat
  > Feature engineering
    - Numerical Features: Standardization
    - Categorical Features: One-hot encoding
  > Modeling
    - Logistic Regression
    - Random Forest


Next Steps
  > Apply cross-validation: K-fold
  > Apply different model: XGBoost
