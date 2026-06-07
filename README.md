# Healthcare-Readmission-Risk-Prediction
Machine Learning project predicting hospital readmission risk using healthcare data. Includes EDA, feature engineering, Random Forest modeling, cross-validation, hyperparameter tuning and business recommendations to support better patient care and reduce readmissions. 


**Business Problem**

Hospital readmissions increase healthcare costs and place additional pressure on hospital resources predicting readmission risk can help improve
patient care and reduce avoidable readmissions.

**Objective**

Build a machine learning model to predict whether a patient is likely to be readmitted using healthcare and hospital visit data.

**Methodology**

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Development
5. Cross Validation
6. Hyperparameter Tuning
7. Model Evaluation

**Tools**

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab


**Key Insights**

- Patient utilization score was the strongest predictor of readmission.
- Previous inpatient admissions significantly increased readmission risk.
- Medication burden contributed to higher readmission probability.
- Patients with multiple diagnoses were more likely to be readmitted.
- Length of hospital stay showed a moderate impact on readmission outcomes.

**Feature Engineering**

The following features were engineered to improve predictive performance:

- Utilization Score
- Medication Burden
- Procedure Intensity
- Chronic Complexity
- Utilization per Diagnosis
- Medications per Diagnosis
- Lab Procedures per Day
- Medications per Day

**Visualizations**

**Target Variable Distribution**
<img width="385" height="234" alt="image" src="https://github.com/user-attachments/assets/9c7d8196-0f1a-4975-923f-2914d4bbc964" />


**Correlation Heatmap**

<img width="497" height="307" alt="image" src="https://github.com/user-attachments/assets/91733c9d-c88d-470f-a9d5-11b73e557b6a" />

**Final Confusion Matrix**

<img width="236" height="150" alt="image" src="https://github.com/user-attachments/assets/c735c2df-b9cb-4952-9fb5-36f1bd2002f1" />

**Feature Importance**

<img width="455" height="268" alt="image" src="https://github.com/user-attachments/assets/28d9c5c0-ae85-42bb-9165-ac310c6d76d9" />



**Business Recommendations**

- Prioritize patients with frequent hospital visits for additional monitoring.
- Strengthen discharge planning for patients with multiple diagnoses.
- Conduct medication reviews for patients with high medication burden.
- Implement readmission risk alerts within hospital information systems.
- Increase post-discharge follow-up for high-risk patients.


