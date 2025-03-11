Cardiovascular Risk Prediction

>Project Summary

The goal of this project was to use machine learning techniques to predict the 10-year risk of future coronary heart disease (CHD) in patients using data from an ongoing cardiovascular study on residents of Framingham, Massachusetts. The dataset consisted of over 4,000 patient records with 15 attributes, representing potential risk factors for CHD, including demographic, behavioral, and medical factors.

>Key Steps in the Project:

  Data Preprocessing:

   -  Handled missing values using median, mode, and KNN imputation techniques.

   -  Identified and removed outliers using the Interquartile Range (IQR) method.

   -  Transformed skewed continuous variables using log and square root transformations.

  Feature Selection and Engineering:

   -  Used Variance Inflation Factor (VIF) to remove multicollinearity.

   -  Created a new feature called pulse_pressure to capture relationships between systolic and diastolic blood pressure.

   -  Removed redundant columns to simplify the dataset.

   -  Identified key features such as age, sex, education, cigs_per_day, bp_meds, prevalent_stroke, prevalent_hyp, diabetes, total_cholesterol, BMI, heart_rate, 
      glucose, and pulse_pressure.

  Handling Imbalanced Data:

   -  Applied SMOTE combined with Tomek links undersampling to balance class distribution.

   -  Scaled the dataset using the Standard Scaler method.

  Model Selection and Evaluation:

   -  Evaluated multiple machine learning models on recall as the primary metric.

   -  Random Forest was chosen as the final model due to its high recall score, which helps in correctly identifying as many patients at risk as possible.

>Problem Statement

The dataset originates from an ongoing cardiovascular study on residents of Framingham, Massachusetts. The classification goal is to predict whether a patient has a 10-year risk of future coronary heart disease (CHD). The dataset contains over 4,000 records with 15 attributes, representing potential risk factors from demographic, behavioral, and medical categories.

>Business Objective

  The objective of this project is to develop a predictive model that can help medical professionals identify patients at high risk of developing CHD over the 
  next 10 years. By accurately predicting risk levels, healthcare providers can:

   -  Implement preventive interventions early.

   -  Optimize treatment plans based on risk factors.

   -  Enhance patient monitoring and lifestyle recommendations.

   -  Reduce the overall burden of cardiovascular diseases through timely predictions.

>Solution to Business Objective

   -  To help medical professionals and healthcare institutions achieve the business objective, the following strategies were applied:

   -  Early Identification of High-Risk Patients: The model predicts individuals with high CHD risk, enabling early preventive measures.

   -  Feature-Based Risk Assessment: Identifying key predictors allows doctors to focus on critical risk factors such as high blood pressure, diabetes, and 
      smoking.

   -  Balancing the Dataset for Fair Predictions: Techniques like SMOTE with Tomek links undersampling ensure that both high-risk and low-risk cases are 
      correctly identified.

   -  Scalability and Deployment: The model can be integrated into medical applications to provide automated risk assessment for patients.

  By implementing these strategies, healthcare institutions can improve patient outcomes, reduce hospitalizations, and enhance overall cardiovascular health 
  monitoring.

>Conclusion

 This project demonstrated the potential of machine learning techniques in predicting the 10-year risk of coronary heart disease (CHD). Key takeaways include:

  -  Data Preprocessing Matters: Handling missing values, outliers, and skewed distributions significantly improved model performance.

  -  Feature Selection is Crucial: Identifying and engineering relevant features enhanced prediction accuracy.

  -  Model Choice and Evaluation: Random Forest was chosen due to its high recall score, ensuring better identification of high-risk patients.

  -  Handling Class Imbalance: The use of SMOTE with Tomek links undersampling improved model generalization.

This project showcases how data-driven approaches can be applied to real-world healthcare challenges, ultimately supporting better decision-making and improving patient care outcomes.

