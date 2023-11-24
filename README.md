# end-to-end-heart-disease-classification
## Features
- Exploratory data analysis (EDA) 
- Model training 
- Model evaluation
- Model comparison 
- Model fine-tuning 
- Feature importance 
- Cross-validation 
- Reporting what we have found 

We're going to take the following approach :
1. Problem definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentations

The following are the features will help to predict our target variable (heart disease or no heart disease).

Creating data dictionary

1. age - age in years
2. sex - (1 = male; 0 = female)
3. cp - chest pain type
   * 0: Typical angina: chest pain related decrease blood supply to the  heart
   * 1: Atypical angina: chest pain not related to heart
   * 2: Non-anginal pain: typically esophageal spasms (non heart related)
   * 3: Asymptomatic: chest pain not showing signs of disease
4. trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
5. chol - serum cholestoral in mg/dl
6. serum = LDL + HDL + .2 * triglycerides
above 200 is cause for concern
7. fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
'>126' mg/dL signals diabetes
8. restecg - resting electrocardiographic results
   * 0: Nothing to note
   * 1: ST-T Wave abnormality
        ** can range from mild symptoms to severe problems
        ** signals non-normal heart beat
   * 2: Possible or definite left ventricular hypertrophy
       * Enlarged heart's main pumping chamber
9. thalach - maximum heart rate achieved
10. exang - exercise induced angina (1 = yes; 0 = no)
11. oldpeak - ST depression induced by exercise relative to rest looks    at stress of heart during excercise unhealthy heart will stress more
12. slope - the slope of the peak exercise ST segment
   * 0: Upsloping: better heart rate with excercise (uncommon)
   * 1: Flatsloping: minimal change (typical healthy heart)
   * 2: Downslopins: signs of unhealthy heart
13. ca - number of major vessels (0-3) colored by flourosopy
   * colored vessel means the doctor can see the blood passing through
   * the more blood movement the better (no clots)
14. thal - thalium stress result
   * 1,3: normal
   * 6: fixed defect: used to be defect but ok now
   * 7: reversable defect: no proper blood movement when excercising
15. target - have disease or not (1=yes, 0=no) (= the predicted attribute)
