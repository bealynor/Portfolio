
# Portfolio
This repository comprises the necessary files for the Portfolio 3.

The dataset is derived from the homeloan records released by the LendingClub.com.

# Objective of the Project
The purpose of this repository is to provide a process flow, and create a model structure and graphical presentation to predict a borrower's credit standing based on his/her profile. 

# Description of Variables 
*credit.policy: This is the label. Its value is 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
*purpose: The purpose of the loan (takes values "creditcard", "debtconsolidation", "educational","majorpurchase", "smallbusiness", “home_improvement” and "all_other").
*int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
*installment: The monthly installments owed by the borrower if the loan is funded.
*log.annual.inc: The natural log of the self-reported annual income of the borrower.
*dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
*fico: The FICO credit score of the borrower.Common FICO scores range from 300 to 850,with higher scores indicating better credit.
*days.with.cr.line: The number of days the borrower has had a credit line.
*revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
*revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
*inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
*delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
*pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments
*not.fully.paid：Whether the borrower will be fully paid or not.

# Summary of Tasks

1. Import cvs file and neccessary functions such as pandas, seaborn, matplotlib, etc.
2. Fill in missing values from the data 
3. Check for outliers and remove them
4. Check for correlation between Credit Policy and other features and remove negative correlations 
5. Convert features that have object types to numerical values in order to use logistical model
6. Split the datasets into training, validation and testing sets using Cross Validation
7. Normalize the dataset
8. Provide a Logistic Regression model and train datasets using K-Fold Cross Validation
9. Proivde a visualization to better understand the model's accuracy


# Overall Findings

From the visualization result, we can clearly see that the model prediction is a good model since both are above 80%, and the training accuracy score (83%) is just slightly lower than the validation accuracy score (84%).


