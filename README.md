# CaseStudy1DDS
Employee Attrition Analysis - MSDS 6306 Case Study 1

#Case Study 1: Employee Attrition Analysis
MSDS 6306: Doing Data Science
Author: Nicholas Alexander Jones
Date: 10/26/2025

#Youtube Presentation Link
https://youtu.be/IcAnoAVLtuo

##Executive Summary
#Business Problem
DDSAnalytics was hired by Frito Lay to identify factors that are driving employee attrition and develop predictive models to reduce turnover costs

#Top 5 Attrition Predicting Variables Used (Top 3 for the Best/Final KNN- Model, Top 5 for the Best/Final NB Model)
1. Overtime (p-value: 2.3e-15
2. Stock Option Level (p-value: 3.7e-12)
3. Job Role (p-value: 3.6e-10)
4. JobInvolvement (p-value: 5.2e-09)
5. JobLevel (p-value: 2.1e-08)

#Model Performance
Final Naive Bayes:
Threshold = .18
Sens = 82.9%
Specificity = 74.1%
Accuracy = 75.48%
Mcnemar's Test P-Value = 9.068e-10

Final KNN Model:
Threshold = .216
Sens = 65.85%
Specificity = 77.73%
Accuracy = 75.86%
Mcnemar's Test P-Value = 1.839e-05

#Business Impact (Per 30% * 870 = 261)
Net Projected Savings (Best NB) = 393,600
Net Projected Savings (Best KNN) = 185,200

##Repository Content
README.md (Executive Summary)
Jones_CaseStudy1.Rmd
Jones_CaseStudy1.html
Case Study 1.pptm

CaseStudy1-data.csv - Training dataset
CaseStudy1CompSet-No-Attrition.csv - Competition Dataset
Case1PredictionsJones_Attrition.csv - Competition Attrition Prediction

##Methodology
Chi_Square tests for categorical variables
Independent t-tests for numerical variables
Significance threshold: p < .05

#Models
Naive Bayes
KNN

#Model Criteria 
Minimum 60% sensitivity and 60% specificity for each model
Maximize Savings

#"#Variables"
Variable analysis/tests and analysis that was used to choose variables for model

#"#Submission"
Code for the attrition prediction of the unknown dataset

##Software
R (Version 4.5.1)

## Origin
Nicholas Jones
Southern Methodist University - MSDS
GitHub: github.com/NicholasJones03/CaseStudy1DDS







