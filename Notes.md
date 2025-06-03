# Heart Disease 

1. **Age**: Patients’ age in years (Numeric)  
2. **Sex**: Gender (Male = 1; Female = 0) (Nominal)  
3. **cp**: Type of chest pain  
   - 0 = typical angina  
   - 1 = atypical angina  
   - 2 = non-anginal pain  
   - 3 = asymptomatic (Nominal)  
4. **trestbps**: Resting blood pressure in mm Hg (Numeric)  
5. **chol**: Serum cholesterol in mg/dl (Numeric)  
6. **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) (Nominal)  
7. **restecg**: Resting ECG results  
   - 0 = normal  
   - 1 = ST-T wave abnormality  
   - 2 = left ventricular hypertrophy (Nominal)  
8. **thalach**: Maximum heart rate achieved (Numeric)  
9. **exang**: Exercise-induced angina (0 = no; 1 = yes) (Nominal)  
10. **oldpeak**: ST-depression induced by exercise relative to rest (Numeric)  
11. **slope**: Slope of peak exercise ST segment  
    - 0 = up-sloping  
    - 1 = flat  
    - 2 = down-sloping (Nominal)  
12. **ca**: Number of major vessels (0–3) colored by fluoroscopy (Nominal)  
13. **thal**: Thalassemia  
    - 0 = NULL  
    - 1 = normal  
    - 2 = fixed defect (no flow)  
    - 3 = reversible defect (abnormal flow) (Nominal)  
14. **target**: Diagnosis of heart disease (1 = disease; 0 = no disease) (Nominal)



## MLP Evaluation

No Training -> Eval Heart Disease
Framingham -> Eval Heart Disease
Framingham ext -> Eval Heart Disease

Heart -> Eval Heart Disease
Heart + Framingham -> Eval Heart Disease
Heart + Framingham ext -> Eval Heart Disease