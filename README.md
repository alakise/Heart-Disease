# Building a Supportive Artificial Neural Network Model in the Diagnosis of Heart Disease | Kalp Hastalığı Tanısında Destekleyici Yapay Nöral Ağ Modeli Oluşturulması
This study is the source code of the project named "Building a Supportive Artificial Neural Network Model in the Diagnosis of Heart Disease" presented at the [2021 Marmara University Student Congress](https://www.marmarastudentcongress.com/). Check dataset on [Kaggle](https://www.kaggle.com/nareshbhat/health-care-data-set-on-heart-attack-possibility) or [UCI.edu](https://archive.ics.uci.edu/ml/datasets/heart+disease). 

## Problem Definition
Given clinical parameters about a patient, can we predict whether or not they have heart disease?
## Features
Explanation of fields in dataset
### Data Dictionary
1. `age` - age in years
2. `sex` - (1 = male; 0 = female)
3. `cp` - chest pain type
    * 0: Typical angina
    * 1: Atypical angina
    * 2: Non-anginal pain
    * 3: Asymptomatic
4. `trestbps` - resting blood pressure (in mm Hg on admission to the hospital) 
5. `chol` - Serum cholesterole in mg/dl
6. `fbs` - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. `restecg` - resting electrocardiographic results
    * 0: Nothing to note
    * 1: ST-T Wave abnormality
    * 2: Possible or definite left ventricular hypertrophy
8. `thalach` - maximum heart rate achieved
9. `exang` - exercise induced angina (1 = yes; 0 = no)
10. `oldpeak` - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
11. `slope` - the slope of the peak exercise ST segment
    * 0: Upsloping: better heart rate with excercise (uncommon)
    * 1: Flatsloping: minimal change (typical healthy heart)
    * 2: Downslopins: signs of unhealthy heart
12. `ca` - number of major vessels (0-3) colored by flourosopy
    * colored vessel means the doctor can see the blood passing through
    * the more blood movement the better (no clots)
13. `thal` - thalium stress result
    * 1,3: normal
    * 6: fixed defect: used to be defect but ok now
    * 7: reversable defect: no proper blood movement when excercising
14. `target` - have disease or not (1=yes, 0=no) (= the predicted attribute)
