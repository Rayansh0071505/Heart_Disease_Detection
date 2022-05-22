# Heart_Disease_Detection

<h2> Problem Definition
In a statement,

<i>Given clinical parameters about a patient, can we predict whether or not they have  hart disease?.

<h2>Data dictionary


<h5><li>age - age in years
    
<li>sex - (1 = male; 0 = female)
    
<li>cp - chest pain type
    
        0: Typical angina: chest pain related decrease blood supply to the heart
        1: Atypical angina: chest pain not related to heart
        2: Non-anginal pain: typically esophageal spasms (non heart related)
        3: Asymptomatic: chest pain not showing signs of disease
    
<li>trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
    
<li>chol - serum cholestoral in mg/dl
    
        <li>serum = LDL + HDL + .2 * triglycerides

        <li>above 200 is cause for concern
    
<li>fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
    
    <li>'>126' mg/dL signals diabetes
<li>restecg - resting electrocardiographic results
    
    0: Nothing to note
    1: ST-T Wave abnormality
        can range from mild symptoms to severe problems
        signals non-normal heart beat
    2: Possible or definite left ventricular hypertrophy
        Enlarged heart's main pumping chamber
    
<li>thalach - maximum heart rate achieved
    
<li>exang - exercise induced angina (1 = yes; 0 = no)
    
<li>oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
    
<li>slope - the slope of the peak exercise ST segment
    
    0: Upsloping: better heart rate with excercise (uncommon)
    1: Flatsloping: minimal change (typical healthy heart)
    2: Downslopins: signs of unhealthy heart
    
<li>ca - number of major vessels (0-3) colored by flourosopy
    
       <li> colored vessel means the doctor can see the blood passing through
       <li> the more blood movement the better (no clots)
<li>thal - thalium stress result
    
       <li> 1,3: normal
       <li> 6: fixed defect: used to be defect but ok now
        <li>7: reversable defect: no proper blood movement when excercising
    
<li>target - have disease or not (1=yes, 0=no) (= the predicted attribute)
