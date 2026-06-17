#Diabetes Risk Analytics 

#Overview :

This project analyzes healthcare and lifestyle factors that contribute to diabetes risk. The project uses data analytics and machine learning techniques to identify important risk factors associated with diabetes and predict diabetes levels based on health indicators.

#Objectives :

Analyze healthcare and lifestyle data related to diabetes.
Identify major factors affecting diabetes risk.
Study the relationship between BMI and diabetes occurrence.
Analyze the impact of blood pressure, cholesterol, smoking, and physical activity.
Visualize diabetes-related patterns and trends.
Predict diabetes levels using Machine Learning.
Support early diabetes risk identification through data analysis.


#Technologies Used :

Python
Pandas
NumPy
Matplotlib
Scikit-Learn
Jupyter Notebook


#Dataset Features :

Diabetes_012
HighBP
HighChol
CholCheck
BMI
Smoker
Stroke
HeartDiseaseorAttack
PhysActivity
Fruits
Veggies
HvyAlcoholConsump
AnyHealthcare
NoDocbcCost
GenHlth
MentHlth
PhysHlth
DiffWalk
Sex
Age
Education
Income


#Machine Learning Model :
Random Forest Classifier

Random Forest Classifier was used to predict diabetes levels based on health indicators such as BMI, blood pressure, cholesterol, smoking habits, physical activity, and age.

#Model Performance :

Algorithm: Random Forest Classifier
Accuracy Score: 84.76%


#Project Workflow :

Data Collection
Data Cleaning
Exploratory Data Analysis (EDA)
Data Visualization
Feature Selection
Train-Test Split
Model Training
Diabetes Prediction
Result Analysis


#Results & Analysis :

#1. Diabetes Distribution Analysis :


This chart shows the distribution of individuals with no diabetes, prediabetes, and diabetes.

Observation: Most individuals belong to the No Diabetes category, while fewer individuals are classified as Prediabetes and Diabetes.


<img width="1143" height="582" alt="Screenshot 2026-06-17 092452" src="https://github.com/user-attachments/assets/4504cfba-86fe-4618-a2b8-552805b3ac8b" />





#2. BMI Category Distribution :


This chart classifies individuals into Underweight, Normal, Overweight, and Obese categories based on BMI values.

Observation: A large number of individuals fall into the Overweight and Obese categories, which are associated with increased diabetes risk.


<img width="1022" height="567" alt="Screenshot 2026-06-17 092856" src="https://github.com/user-attachments/assets/f1a68cb4-a317-4952-9e1f-877ca4a55d2b" />



#3.Age Distribution :


This chart shows the distribution of individuals across different age groups in the dataset.

Observation: Most records belong to middle-aged and older adults. The number of diabetes cases tends to increase with age, indicating that age is an important factor associated with diabetes risk. Older age groups show a higher concentration of individuals compared to younger age groups.


<img width="1020" height="571" alt="Screenshot 2026-06-17 093716" src="https://github.com/user-attachments/assets/5f84b544-d6c5-4275-96a4-15a17c67e17b" />




#4. High Blood Pressure vs Diabetes :


This visualization shows the relationship between high blood pressure and diabetes occurrence.

Observation: Individuals with high blood pressure have a higher percentage of diabetes compared to those without high blood pressure.


<img width="1001" height="562" alt="Screenshot 2026-06-17 093013" src="https://github.com/user-attachments/assets/4ecc801f-618d-4ada-b0df-035b4f8afa85" />




#5. Smoking vs Diabetes :


This chart analyzes the impact of smoking habits on diabetes occurrence.

Observation: Smoking is associated with a higher diabetes prevalence compared to non-smokers.


<img width="1212" height="565" alt="Screenshot 2026-06-17 093142" src="https://github.com/user-attachments/assets/c0a0a8e6-2998-4813-b90d-ee36fd032385" />




#6. Physical Activity vs Diabetes :


This visualization compares diabetes occurrence among physically active and inactive individuals.

Observation: Individuals with regular physical activity tend to have lower diabetes prevalence.


<img width="1027" height="598" alt="Screenshot 2026-06-17 093307" src="https://github.com/user-attachments/assets/611e3e8f-f0c3-4108-8b67-d36f8fbedb81" />




#7. General Health vs Diabetes :


This visualization analyzes how general health condition relates to diabetes occurrence.

Observation: Poor general health is associated with a higher percentage of diabetes cases.


<img width="1052" height="587" alt="Screenshot 2026-06-17 093427" src="https://github.com/user-attachments/assets/6c9785ae-9f04-4584-ae0f-c4c082039075" />




Conclusion :

This project analyzes healthcare and lifestyle data to understand the major factors contributing to diabetes risk. The analysis indicates that BMI, high blood pressure, cholesterol levels, smoking habits, physical activity, and general health are strongly associated with diabetes occurrence. The Random Forest Classifier provides effective predictions and supports early diabetes risk identification.
