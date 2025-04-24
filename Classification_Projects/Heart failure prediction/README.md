## Project Title : Heart Failure Prediction

**Technologies Used:** Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, scipy --- Languages: Python.

**Project Objective:** The main aim of this project is to develop a predictive model for heart disease using patient data and to identify key risk factors through exploratory data analysis (EDA), also help with early detection and treatment of heart diseases.

**Table of contents**

Data Loading
Data Exploration
Data Preprocessing
Exploratory Data Analysis (EDA)
Modeling
Evaluation Metrics
Conclusion

**The project follows a structured pipeline as outlined below:**

**1. Data Loading:** Loaded the dataset and inspect its structure. 

**2. Data Exploration:** Understand the dataset by checking distributions, missing values, datatypes and key statistics.

**Data challenges**

variables such as Sex, ChestPainType, RestingECG, ExerciseAngina, ST_Slope consists of categorical data. So, it need to convert into nurmerical data.

**3. Data Preprocessing:** By using Encoding technique like OrdinalEncoder() those variables are converted into numerical data. This step is performed after EDA.

**4. Exploratory Data Analysis (EDA):** performed univariant and bivariant analysis.

**Insights Observed:**

   - Gender (male), asymptomatic chest pain, exercise-induced angina, flat ST slope, and higher cholesterol are strong indicators of heart disease.
   - Numerical variables such as lower MaxHR and higher Oldpeak also correlate significantly with heart disease.
     
**5. Modeling:**

   - Logistic Regression
   - Decision Tree
   -  Random Forest
   -  XGBoost
   -  AdaBoost
   -  Gradiant Boosting
   -  KNN
   -  SVM
      
**6. Evaluation :** Evaluated models using metrics like accuracy, precision, recall, F1-score and confusion matrix.

**7. Conclusion:**

EDA identified significant risk factors such as chest pain type, exercise-induced angina, ST slope, and Oldpeak, providing valuable insights into heart disease patterns. Machine learning models were developed, with Random Forest and Gradient Boosting achieved the highest accuracies with 88%. These models demonstrate strong potential for reliable heart disease prediction, supporting early diagnosis and improving patient outcomes.
