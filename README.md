# Credit-Card-Lead-Prediction
Hackathon

Steps Followed:

1. Importing Libraries
2. Perfoming Data Cleaning, Log Transformation
3. Used IterativeImputer to impute missing values thus improving the performance of the ML model
4. Log Transformation helped in converting the skewed data into Normal Distribution
5. Engineered new Features by encoding the categorical data using LabelEncoder, BinaryEncoder
6. Splitted the Dataset into training and testing
7. Tuned the Hyper parameters for the ML model to use by GridSearchCV
8. Found out the best performing model using Stratified K-Fold Cross Validation
9. Resulted in a ROC_AUC score of 0.87454
