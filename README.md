# Credit Card Approval Prediction

# Project Overview
This project aims to develop a machine learning model that predicts whether an applicant should be approved for a credit card based on various socio-economic and financial factors. The goal is to use different classification algorithms to optimize accuracy and provide insights into key approval criteria.
# Dataset Description
The dataset contains information about credit card applicants, including their demographics, financial status, and employment details. The features considered for prediction are:

Features:

- Applicant_Gender: Gender of the applicant 
- Owned_Car: Whether the applicant owns a car 
- Owned_Realty: Whether the applicant owns real estate property 
- Total_Children: Number of children the applicant has
- Total_Income: Applicant's annual income
- Income_Type: Type of income source 
- Education_Type: Applicant's highest education level
- Family_Status: Marital status of the applicant
- Housing_Type: Applicant's living arrangements
- Owned_Mobile_Phone: Whether the applicant owns a mobile phone
- Owned_Work_Phone: Whether the applicant owns a work phone
- Owned_Phone: Whether the applicant owns a landline phone
- Owned_Email: Whether the applicant owns an email address
- Job_Title: Applicant’s current job title
- Total_Family_Members: Number of family members in the applicant's household
- Applicant_Age: Applicant’s age
- Years_of_Working: Total years of employment
- Total_Bad_Debt: Number of previous bad debts
- Total_Good_Debt: Number of previous successfully repaid debts
## Data Preprocessing

Data Cleaning:
- Handling missing values by either removing records with significant missing data or imputing values.
- Converting categorical variables into numerical format using one-hot encoding.
- Standardizing numerical features such as income, age, and years of working .
  
 ## Model Selection & Training 
 Multiple machine learning algorithms are tested to find the best-performing model

 Algorithms Used:
 - Logistic Regression
 - Decision Tree Classifier
 - Random Forest Classifier
 - XGBoost
   
 
 
  

