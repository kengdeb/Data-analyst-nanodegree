# Loan data from Prosper
## by Nuttapong Auetavonarnun


## Dataset

> This document explores dataset comprising of 113,937 loans with 81 variables on each loan, 
including loan amount, borrower rate (or interest rate), current loan status, borrower income etc.
The dataset can be found in https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv
with data dictionary here: https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0

## Summary of Findings

> In the exploration, I am looking at what could be factors to be able to explain loan defaut. And what are the factors driven loan borrow rate.
The key factors I investigated are loan term, credit grade, income range, occupation, borrow rate, loan original amount, state, and debt to income ratio.

Few interesting relationships have been identified. First, the higher the credit grade, the lower the percentage of loan default. Second, with higher credit 
grade (AA, A) or higher income range, the borrower is intend to get lower borrower rate. Third, debt to income ratio for default borrower has higher than not 
default borrower whatever credit grade. Third, stated monthly income and debt to income ratio don't seem to make different between default and not default 
customer except when borrower has high stated monthly income plus low debt to income ratio. Finally, each state has different percentage of default. ND (Nevada) shows highest number of default almost 14%, while the lowest state seem to be SC (Sacramentol)
with default rate less than 1%

## Key Insights for Presentation

> For the presentation, I focus on what contributed to loan default.
I start by look at credit grade vs loan default, follow by which state has highest and lowest loan default.
Then I showed what debt to income raton effect to loan default. And finish with effect of loan term to loan default.