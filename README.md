# Analysis-on-predicting-diabetes-using-ML

#  Diabetes Prediction using Machine Learning

##  Project Overview
Diabetes is one of the most common lifestyle-related diseases caused by ineffective insulin use, leading to high blood sugar and severe health issues such as heart, kidney, and vision problems.  
Early prediction plays a crucial role in enabling lifestyle changes and timely treatment.  

This project uses machine learning models to predict whether an individual is diabetic or non-diabetic based on health indicators like BMI, glucose level, age, and family history.                                                                   ##  Objectives
- Analyze health-related data and identify factors linked to diabetes.  
- Build a predictive machine learning model to classify individuals as diabetic or non-diabetic.  
- Compare the performance of multiple algorithms and derive insights.                                                           ## Dataset
- Features: 8 input features + 1 target (Outcome)  
- Data Quality Issues:  
  - Zero values in some columns treated as missing  
  - Outliers detected in several features  
  - Slight class imbalance (more non-diabetic cases)  
- Preprocessing Steps:  
  - Handling missing values  
  - Outlier treatment  
  - Scaling and normalization  
  - Feature engineering and correlation checks 
## Exploratory Data Analysis (EDA)
- Distribution of diabetic vs non-diabetic patients: 71.5% Non-diabetic, 28.5% Diabetic  
- Visualization: Histograms, Pie charts, Count plots, Pair plots, Heatmaps  
- Feature importance: Glucose, BMI, and Age were the strongest predictors                                                                  - Best Performing Models: SVM & KNN (~83% accuracy)  
- Ensemble Models (Bagging, Boosting, Random Forest) also gave strong performance.                                             ##  Key Insights
- Glucose is the most significant predictor of diabetes.  
- BMI & Age also strongly influence predictions.  
- Decision Tree showed the weakest performance (~72%).  
- Ensemble methods (Boosting, Bagging, Random Forest) offered more balanced results and are recommended for real-world deployment. 
- BMI & Age also strongly influence predictions.  
- Decision Tree showed the weakest performance (~72%).  
- Ensemble methods (Boosting, Bagging, Random Forest) offered more balanced results and are recommended for real-world deployment.
