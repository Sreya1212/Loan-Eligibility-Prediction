# Loan Eligibility Prediction using Python

The Loan Eligibility Prediction System is a machine learning project designed to automate the process of determining whether an applicant is eligible for a loan based on their personal and financial information. 
The project involves collecting historical loan application data available on Kaggle. The dataset includes features such as applicant's gender, income, credit history, employment status, loan amount, loan term, and other relevant factors. Additionally, the dataset contains the target variable indicating loan approval status - 1 or 0 (eligible or not eligible).

## Approach:
The project follows a systematic approach to develop and deploy a predictive model for loan eligibility prediction:
### 1. Data Collection: 
Gathered historical loan application data from Kaggle.

loan-train.csv is used to build model and train it

loan-test.csv is used to validate it.

### 2. Data Preprocessing: 
Dataset is cleaned by handling missing values using mean and mode, normalizing values by calculating log. 

Performed feature engineering to create new features and transform existing ones. 

Categorical variables are converted to numerical representations using encoding techniques.

### 3. Model Selection: 
Appropriare machine learning models for loan eligibility prediction is selected such as Decision tree and Naive Bayes Classifier.

### 4. Model Training: 
Dataset is splitted into training and testing sets which is then used to train the model and predict values, which is then used to compare with test set to calculate accuracy.

### 5. Testing: 
The built model is used to predict loan eligibility status for new test data. 1 represents customers are eligible for loan, 0 represents ineligibility.
   
