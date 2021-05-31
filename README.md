# Credit-Card-Lead-Prediction
Hackathon

Notebooks descriptions:
1. Credit Card Lead Prediction.ipynb - Python notebook with ML models manually called and predicted by creating functions
2. Credit_Lead_Prediction_PyCaret.ipynb - Python notebook with Pycaret implementation from model development to pipeline deployment.
3. Loading the pipeline and predictions - Shows the loading of the pickle file and predictions on the test data.

Steps Followed in Credit Card Lead Prediction.ipynb notebook:
1.	Importing Libraries
 
Libraries imported were numpy, Pandas, Matplotlib, Seaborn, Sci-kit learn, Category Encoders, XGBOOST, CATBOOST, LGBOOST
2.	Perfoming Data Cleaning, Log Transformation
•	Performed Exploratory Analysis and found out the missing values and the data distributions
•	Used Iterative Imputer to impute the missing values using Gaussian Naïve Bayes estimator. It performs effective imputation of missing values and gives better performing model.
 
 
3.	Log Transformation helped in converting the skewed data into Normal Distribution
Checked for the skewness of the data and converted the salary column into normal distribution by applying Log transformation.

   
4.	Engineered new Features by encoding the categorical data using LabelEncoder, BinaryEncoder
•	Created new features using the existing features using BinaryEncoder, LabelEncoder to automate the process of encoding variables
 
5.	Splitted the Dataset into training and testing 

6.	Tuned the Hyper parameters for the ML model to use by GridSearchCV

 
7.	Found out the best performing m odel using Stratified K-Fold Cross Validation

8.	Resulted in a ROC_AUC score of 0.87435

 


