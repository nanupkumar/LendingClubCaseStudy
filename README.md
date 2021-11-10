# Lending Club Case Study
We work for a consumer finance company which is specialised in lending various types of loans to urban customers. Upon receiving a loan application, the company has to approve/reject the request based on the applicant’s profile.
The following are two types of risks associated with the bank’s decision,
 - Loss of business: Not approving the loan even if the applicant is likely to repay.
 - Financial Loss: Approving the loan when the applicant is likely to default.

The aim of this case study is to identify the traits of risky loan applicants using Exploratory Data Analysis - EDA. In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. This knowledge helps the company during Risk Assessment process and approving loan for the right applicants thereby avoiding potential loss of business and also at the same time minimising the financial/credit loss*. 
*Credit loss is the amount of money lost by the lender when the borrower refuses to pay the money owed.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
The project broadly falls under the category of Risk Analytics. 
We work for a consumer finance company which is specialised in lending various types of loans to urban customers. Upon receiving a loan application, the company has to approve/reject the request based on the applicant’s profile.
The following are two types of risks associated with the bank’s decision,
 - Loss of business: Not approving the loan even if the applicant is likely to repay.
 - Financial Loss: Approving the loan when the applicant is likely to default.

The aim of this case study is to identify the traits of risky loan applicants using Exploratory Data Analysis - EDA. In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. This knowledge helps the company during Risk Assessment process and approving loan for the right applicants thereby avoiding potential loss of business and also at the same time minimising the financial/credit loss*. 
*Credit loss is the amount of money lost by the lender when the borrower refuses to pay the money owed.

The dataset contains complete loan data for all loans issued through the time period 2007 t0 2011 by the financial organisation used in this project.

The predmoninat approach followed is to use the EDA techniques listed below to arrive at the necessary conclusions:
 - Data Cleaning
 - Data Manipulation
 - Derived feature extraction
 - Bivariate analysis through Plotting


## Conclusions
 - Customers with annual income < 40000 are most likely to default
 - Loans with very high (>15%) of interest rate are most likely to be charged-off
 - Loan Amounts of > 15000 are most likely to be defaulted
 - Loans taken with the purpose of Small Business loans are most likely to be defaulted
 - Grades in the order of G, F, E and D have high chances of default


## Technologies Used
- Libraries used:
    - pandas
    - numpy
    - matplotlib
    - datetime
    - seaborn
- Project coded using the iPython Jupyter notebook.
- Python version used 3.5.2.


## Acknowledgements
Give credit here.
- This project was created as part of the project activity for the ML and AI course at Upgrad.
- Coding references used from the following web-sites for the needs of self help and syntax corrections:
    - https://seaborn.pydata.org/tutorial/distributions.html
    - https://seaborn.pydata.org/tutorial/axis_grids.html
    - https://stackoverflow.com/
    

## Contact
Created by [@nanupkumar] - feel free to contact me!
