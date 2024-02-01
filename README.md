# Diabetes_prediction_model


Predicting Diabetes - Model Evaluation

Dataset Description:
gender:
Data Type: Categorical variable (Female/Male)
Description: Patient's gender.

age:
Data Type: Numeric variable (float)
Description: Patient's age.

hypertension:
Data Type: Binary variable (0/1)
Description: Value of 1 indicates whether the patient has hypertension, and 0 indicates no hypertension.

heart_disease:
Data Type: Binary variable (0/1)
Description: Value of 1 indicates whether the patient has heart disease, and 0 indicates no heart disease.

smoking_history:
Data Type: Categorical variable (never/current/former/No Info)
Description: Patient's smoking history.

bmi:
Data Type: Numeric variable (float)
Description: Body Mass Index (BMI) of the patient.

HbA1c_level:
Data Type: Numeric variable (float)
Description: Hemoglobin A1c (HbA1c) level - a measure of diabetes control. Expresses the patient's average blood glucose over the past two to three months.

blood_glucose_level:
Data Type: Numeric variable (int)
Description: Patient's blood glucose level.

diabetes:
Data Type: Binary variable (0/1)
Description: Value of 1 indicates the presence of diabetes, and 0 indicates its absence.


Model Performance:
Logistic regression:
Accuracy: 95.97%
Macro Precision: 92.71%
Macro Recall: 80.33%
Macro F1 Score: 85.24%

Logistic regression with SMOTEENN:
Accuracy: 95.93%
Macro Precision: 95.90%
Macro Recall: 95.95%
Macro F1 Score: 95.92%

XGBoost:
Accuracy: 93.51%
Macro Precision: 78.78%
Macro Recall: 87.10%
Macro F1 Score: 82.22%

KNN:
Accuracy: 95.85%
Macro Precision: 93.85%
Macro Recall: 78.55%
Macro F1 Score: 84.25%

RandomForest:
Accuracy: 96.67%
Macro Precision: 96.32%
Macro Recall: 82.15%
Macro F1 Score: 87.69%

Summary:
The dataset consists of various patient attributes, including demographic information, medical history, and diabetes-related indicators. The goal is to predict the presence or absence of diabetes based on these features.

Five different models were trained and evaluated on the dataset. The RandomForest model achieved the highest accuracy (96.67%) and macro F1 score (87.69%) among the models, making it a promising candidate for predicting diabetes in this context. Further fine-tuning and exploration of feature importance could enhance model performance.
