# Heart Disease Prediction
## Predicting heart-disease using ML classification

The purpose of this project is to use a set of 303 patient health records containing various patient demographic characteristics and cardiovascular health related test metrics to predict whether or not a patient will be diagnosed with heart disease. 

After testing multiple machine learning models, I found that the K-Nearest Neighbors Algorithm performed most optimally at predicting heart disease, outperforming even Gradient Boost and Random Forest. The performance of the optimized KNN model is as follows:

- accuracy:  0.857
- precision:  0.854
- recall:  0.833
- f1 score:  0.843

**Attribute Descriptions**
- **age**: age of the patient
- **sex**: sex of the patient (1 = male, 0 = female) 
- **chest_pain**: pain level between 1-4, higher number = lower odds of heart attack (1= typical, 2 = atypical, 3 = non-anginal pain, 4 = asymptomatic) 
- **rest_bp**: resting blood pressure (in mm HG on admission) 
- **cholesterol**: serum cholesterol in mg/dl, higher = higher odds of heart attack 
- **fast_bs**: fasting blood sugar > 120 mg/dl (1 = true, 0 = false), indicative of diabetes 
- **rest_ecg**: resting electrocardiographic results (0 = normal, 1 = ST wave abnormality, 2 = left ventricular hypertrophy)
- **max_hr**: max heart rate achieved 
- **exercise_angina**: exercised induced angina, or chest pain, (1 = yes, 0 = no) 
- **st_depression**: difference in ECG value at rest vs. after exercise, measured as an ST depression 
- **st_slope**: slope/tangent of the peak ST depression segment (1 = upsloping, 2 = flat, 3 = downsloping) 
- **blocked_vessels**: number of blocked heart vessels (0-3) 
- **thalassemia_type**: types of thalassemia, an inherited blood disorder which inhibits hemoglobin, (3 = normal; 6 = fixed defect; 7 = reversable defect) 
- **heart_disease (target)**: 0 = absence, 1,2,3,4 = some degree of presence

**Original Data Source**: 
- 1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
- 2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
- 3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
- 4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.
- https://archive.ics.uci.edu/ml/datasets/Heart+Disease
- Permissions: Open source, data has been anonymized, no sensitive information included

