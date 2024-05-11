# Project Title: Loan Eligibility Prediction

## Problem Statement 
In the banking sector, loan approval processes traditionally involve extensive document verification and criteria validation, leading to time-consuming procedures. To streamline this process and expedite loan eligibility decisions, there is a need for a predictive system. The objective of this project is to leverage data science and machine learning algorithms to develop a classification model. This model will categorize loan applicants as either eligible or ineligible based on the information provided in their loan application form. 

## Abstract:
This project aims to predict loan eligibility using machine learning algorithms, specifically Decision Tree and Naive Bayes. The data used was analyzed for its distribution, outliers, and missing values before being pre-processed. Independent and dependent variables were identified, and training and test sets were split. Categorical variables were converted to numeric format, and the data was scaled for optimal model performance.

## Methodology:
### 1. Exploratory Data Analysis (EDA):
       • Summarize key statistics and visualize data distribution.
       • Identify outliers and handle them appropriately.
       • Analyze skewness and perform transformation if necessary.
### 2. Data Pre-processing:
      • Handle missing values through imputation or deletion.
      • Normalize numerical features using techniques like scaling.
      • Encode categorical variables using one-hot encoding or label encoding.
### 3. Model Training:
      • Decision Tree:
        ‣ Train a decision tree model and analyze its performance.
        ‣ Discuss limitations observed in the decision tree model's accuracy (approximately 66%).
     • Naive Bayes:
       ‣ Train a Naive Bayes model and evaluate its performance.
       ‣ Compare the accuracy with the decision tree model (approximately 82%).
       ‣ Analyze the improvement in accuracy and discuss the suitability of Naive Bayes for this task.
### 4. Predicting Loan Eligibility for New Data:
       • Apply the trained model (Naive Bayes) to predict loan eligibility for new data.
       • Discuss the process of cleaning and preparing new data for prediction.
       • Interpret the predicted values and their significance.
       
## Results:
    • The Naive Bayes model achieved a significantly higher accuracy (82%) compared to the Decision Tree model (66%).
    • This suggests Naive Bayes is a more suitable algorithm for predicting loan eligibility based on the given data.
    • Key factors influencing loan eligibility can be identified through model analysis.

## Disclaimer:
This project is for educational purposes only and should not be used for real-world financial decisions.
