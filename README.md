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
Logistic Regression:

Accuracy: 95.67%
Macro Precision: 90.74%
Macro Recall: 80.75%
Macro F1 Score: 84.88%
Comment: Logistic Regression performs well overall, with high accuracy and a balanced trade-off between precision and recall.

Logistic Regression with SMOTEENN:

Accuracy: 87.11%
Macro Precision: 69.61%
Macro Recall: 88.78%
Macro F1 Score: 74.11%
Comment: The model with SMOTEENN shows a decrease in accuracy but an improvement in recall, indicating better identification of positive instances, at the cost of precision.

XGBoost:

Accuracy: 91.67%
Macro Precision: 75.37%
Macro Recall: 89.79%
Macro F1 Score: 80.27%
Comment: XGBoost performs well, with a good balance between precision and recall, providing high accuracy.

K-Nearest Neighbors (KNN):

Accuracy: 95.91%
Macro Precision: 92.27%
Macro Recall: 80.96%
Macro F1 Score: 85.54%
Comment: KNN achieves high accuracy with strong precision, but slightly lower recall compared to Logistic Regression.

Random Forest:

Accuracy: 96.73%
Macro Precision: 94.90%
Macro Recall: 84.14%
Macro F1 Score: 88.62%
Comment: Random Forest outperforms other models with the highest accuracy and a good balance between precision and recall.

Overall Recommendation:
Based on the provided metrics, Random Forest appears to be the most effective model for predicting the diabetes dataset, as it achieves the highest accuracy and a balanced trade-off between precision and recall. Consideration should also be given to the specific goals and requirements of the application, as different models may be preferred depending on the emphasis on precision or recall.
