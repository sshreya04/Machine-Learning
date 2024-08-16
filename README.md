**Heart Disease Prediction Model**

**Objective**

The objective of this project is to build a classification model that predicts the likelihood of heart disease in a patient based on various health and lifestyle features.

**Dataset and Features**

The dataset used contains several features that are crucial in predicting heart disease. Below is a list of the features along with their descriptions:

sex: Male (0) or Female (1); (Nominal)
age: Age of the patient; (Continuous)
currentSmoker: Whether or not the patient is a current smoker (Nominal)
cigsPerDay: The number of cigarettes that the person smoked on average in one day (Continuous)
BPMeds: Whether or not the patient was on blood pressure medication (Nominal)
prevalentStroke: Whether or not the patient had previously had a stroke (Nominal)
prevalentHyp: Whether or not the patient was hypertensive (Nominal)
diabetes: Whether or not the patient had diabetes (Nominal)
totChol: Total cholesterol level (Continuous)
sysBP: Systolic blood pressure (Continuous)
diaBP: Diastolic blood pressure (Continuous)
BMI: Body Mass Index (Continuous)
heartRate: Heart rate (Continuous)
glucose: Glucose level (Continuous)
10 year risk of coronary heart disease (CHD): Binary "1" means "Yes", "0" means "No" - Target Variable

**Steps Performed**

1. Imported Libraries
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training
5. Model Evaluation

**Analysis**

After hyperparameter tuning, the Random Forest model achieved the highest test accuracy (80%), indicating its strong suitability for this classification task.
The Support Vector Machine (SVM) also performed well with an accuracy of 72%, making it a strong alternative.
The Decision Tree model, even after tuning, could not surpass the accuracy achieved by SVM and Random Forest.

**Conclusion**

The Random Forest model proved to be the most effective in predicting heart disease, with the highest accuracy of 80%. The insights from this model can potentially guide healthcare providers in identifying at-risk patients more accurately.
