                     Medical Insurance Charges Prediction

Project Overview:
This project was basically about Exploratory Data Analysis to identify which features effected the insurance cost the most 
and use a ML algrithm to train the model and evaluate it. It involves a complete datascience workflow from data cleaning and
exploratory analysis to model training, hyperparameter tuning and performance evaluation.
The main objectives were:
1. To perform data cleaning and preprocessing
2. To conduct EDA to identify and visualize the relationship of different attributes
3. To determine the predictive power of ML
4. To understand and illustrate how this type of model can increase the efficiency and profitbaility of health insurance companies.

 Key Features and Methodology:
 1. Data Loading & Cleaning: The dataset Medical_insurance.csv was loaded. The initial inspection confirmed that there were no null
    values in the data set.
 2. EDA: In the Exploratory Data Analysis Visualization were used to explore relationship, to understand combined effect and visualize
    effect according to the regions between charges and key variables like smoker, region, children, and sex.
  3. Feature Engineering:<br>
   a. smoker_binary(0/1)<br>
   b. bmi_category and bmi_numeric-Binning and encoding for visualization(categorizing BMI into groups like Very Low, Low, Medium, High,
     Very High)<br>
   c. Age_interval: Binning for data visualization(Categorizing age into Young, Early Middle Age, Late Middle Age, Senior)
  4. Model Training:
     The final feature set for the model included age, bmi, children, smoker_binary, bmi_numeric, age_interval, and one_hot encoded region
     variables. <br>
     A Random Forest Regressor was selected and optimized using GridSearchCV to find the best parameters (like max_depth and n_estimators)

 Results
 The machine learning model demonstrated a strong ability to predict medical insurance charges.
 <br> Model: Random Forest Regressor <br>
 R^2 Score(Test Set): 0.946 <br>
 This R^2 score of 0.946 indicates that the model explains approximately 94.6% of the variance in medical charges, suggesting it is highly 
 effective for making accurate predictions of medical expenses.

 Technology Used:
 1. Python
 2. Pandas(for Data Manipulation)
 3. Numpy(for numerical operations)
 4. Matplotlib & Seaborn (for datavisualization)
 5. Scikit-learn (for machine learning model Development)




     
