# lending-club-loan-analysis
This R markdown file contains analysis of loans on Peer-to-Peer lending website LendingClub. 
Data cleaning, outlier analysis, and profiling has been done to condition data and compare performance of classifiers such as Logistic Regression, Linear Discriminant Analysis, and Random forests considering metrics such as Specificity, Sensitivity, and AUC in ROC.


Peer-to-peer (P2P) lending has transformed how people have access to credit and investing, as it connects borrowers and lenders, both of whom are individuals. Whether it be debt payment, small business growth, or investment in the future, these individuals, who might not qualify for lending practices by stereotypical measures can now participate in this ecosystem and help each other.

Lending Club is a pioneer in the P2P industry. Since 2007, it has over 26 billion dollars in loans to more than 1.5 million borrowers. Lending Club verifies if both investors and borrowers meet their criteria for a transaction. However, P2P lending poses a substantial risk for the lenders because the deposits are not secured, or FDIC insured. As a result, the lending practice can result in a loss for investors if a borrower defaults.

Our objective, therefore, in this project, is to build a classification model that will predict whether a borrower will default or not. We have used Lending Club’s loan data from 2007-2015, which includes pertinent payment and borrower’s information. The original dataset lending club is a matrix of 2260668 observations and 145 features.

Project Breakdown - 

Introduction: Data and Problem Summary

Data Cleaning and Feature Selection

Extracting Relevant Features

Addressing Missing Values

Detecting Outliers

Exploratory Data Analysis

Methodology

Selected Models

Model 1: Logistic Regression

Model 2: Linear Discriminant Analysis

Model 3: Random Forest

Discussion and Conclusion
