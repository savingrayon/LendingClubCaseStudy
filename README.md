## Project Name - 
Lending Club Project details

## Project Description -
The project focuses on conducting Exploratory Data Analysis (EDA) for a consumer finance company that specializes in lending loans. The aim is to analyze past loan data from 2007 to 2011 to identify patterns that could predict whether an applicant is likely to default. The dataset contains details about borrowers who either fully repaid the loan, are currently paying it, or defaulted (charged-off). By identifying key variables that influence the likelihood of default, the company can optimize loan approval decisions and mitigate financial losses due to credit risk. The insights from this analysis will help the company reduce credit losses and enhance its risk assessment models.
This project will involve univariate, bivariate, and multivariate analysis along with relevant visualizations to extract meaningful insights.

## Table of Contents
* General Info - 
The project aims to analyze a dataset of loan applications and identify key factors that influence whether a borrower is likely to default on a loan. This will enable the finance company to make informed lending decisions and reduce potential credit losses.

* Technologies Used - Exploratory Data Analysis(EDA), Python

* Conclusions - 
The analysis reveals clear trends between loan attributes and outcomes:
1. High-interest rates are associated with a higher risk of default, indicating that riskier loans with higher interest rates are more prone to being Charged Off. Lenders should carefully evaluate borrowers for loans with interest rates on the higher end.
2. Loan amounts play a significant role in determining loan outcomes. Smaller loans are more likely to be repaid in full, while larger loans show a higher likelihood of either remaining active (Current) or defaulting (Charged Off). Lenders might need to apply stricter risk assessments or offer more flexible repayment terms for larger loans.
3. Correlations between different loan-related factors (e.g., loan amount, funded amount, installment) are expected, but no strong predictors stand out individually. The risk of default seems to be driven by a combination of interest rate, loan amount, and borrower-specific factors like delinquency history.

* Acknowledgements - I would like to express my sincere gratitude to my mentors and colleague Puneet Mathur for their invaluable guidance and support throughout the course of this project. Special thanks to  Upgrad for offering the resources necessary to complete this work. Finally, I appreciate the encouragement from my friends, whose support kept me motivated.

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This project involves analyzing loan application data from 2007 to 2011 to identify key factors influencing the likelihood of default. The company, a major player in consumer finance, faces two main risks: losing business by rejecting creditworthy applicants and suffering financial losses by approving risky applicants. The goal is to reduce credit loss by using Exploratory Data Analysis (EDA) to discover patterns that indicate a borrower's default risk. The dataset includes borrower details, loan attributes, and loan statuses (fully paid, current, or charged-off). Through this analysis, the company can refine its lending decisions and minimize defaults.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

1.Interest Rate Insights:
Higher interest rates are correlated with a higher likelihood of loans being Charged Off (defaulted). Loans with lower and moderate interest rates tend to have better repayment outcomes, as seen with the Fully Paid category having the lowest median interest rate.
Interest rates for Current loans are quite similar to those of Charged Off loans, indicating that high-interest loans that haven't defaulted yet may still pose a risk.

2.Loan Amount Insights:
Fully Paid loans typically have smaller loan amounts, whereas Charged Off and Current loans show larger median loan amounts. This suggests that smaller loans are easier for borrowers to repay, while larger loan amounts increase the risk of default.
The larger variability in loan amounts for Current loans indicates that larger loans tend to remain active for longer, though they may eventually either be repaid or charged off.

3.Correlation Matrix Insights:
Strong correlations between some variables (e.g., between loan amount, funded amount, and installment) suggest that these variables are tightly related, with larger loan amounts leading to higher installments.
Variables related to delinquency, such as delinq_2yrs, chargeoff_within_12_mths, and pub_rec_bankruptcies, show some degree of correlation with each other, indicating that past delinquency is a good predictor of future credit risk.
The weaker correlations across most variables suggest that predicting default risk requires looking at multiple factors, with no single variable being a strong determinant on its own.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
python version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
I would like to express my sincere gratitude to my mentors and colleague Puneet Mathur for their invaluable guidance and support throughout the course of this project. Special thanks to  Upgrad for offering the resources necessary to complete this work. Finally, I appreciate the encouragement from my friends, whose support kept me motivated.



## Contact
Created by Manohar Ganesh Kulkarni [@mayurklk]  and Puneet Mathur[@savingrayon]


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
