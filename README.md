# HeartDiseasePrediction

Dataset
* From Kaggle "Heart Attack Analysis & Prediction Dataset" (https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset) <br>
* Dataset: 13 columns/features and 1 target <br>
* Target: less chance of heart attack (0) and more chance of heart attack (1) <br>

Feature Detail
* Age: age of patient (numerical data) <br>
* Sex: sex of the patient (categorical data) <br>
* exang: exercise induced angina, yes <1> and no <0> (categorical data) <br>
* ca: number of major vessels <0 - 3> (categorical data) <br>
* cp: chest pain type (categorical data) <br>
    - Value 1: typical angina <br>
    - Value 2: atypical angina <br>
    - Value 3: non-anginal pain <br>
    - Value 4: asymptomatic  <br>
* trtbps: resting blood pressure (numerical data)   <br>
* chol: cholestoral in mg/dl fetched via BMI sensor (numerical data) <br>
* fbs: fasting blood sugar, > 120 mg/dl <1>, otherwise <0> (categorical data) <br>
* rest_ecg: resting electrocardiographic results (categorical data) <br>
    - Value 0: normal <br>
    - Value 1: having ST-T wave abnormality <br>
    - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria <br>
* thalach: maximum heart rate achieved (numberical data) <br>


Approach
* EDA for numerical and categorical dat <br>
* Feature engineering <br>
    - Numerical Features: Standardization <br>
    - Categorical Features: One-hot encoding <br>
* Modeling <br>
    - Logistic Regression <br>
    - Random Forest <br>


Next Steps
* Apply cross-validation: K-fold <br>
* Apply different model: XGBoost
