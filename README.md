# Prosper-Loan-Data-Analysis

## Dataset

The Prosper loan dataset consists of 113937 loan entries with 81 varibles .The varibles are majorly:

Information about the borrower: The borrower's fundamental characteristics, such as annual income, employment status, interest rate, and loan status.
Information on loan performance: metrics assessing the risk of the loans, including Prosper score and bank card usage, etc.
The dataset can be found in the :https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.



## Summary of Findings

In the exploration, I found the borrower rate and loan original amount  are negatively correlated,supporting the idea that the lower the APR, the greater the loan amount.

The loan original amount is positively correlated with the stated monthly income with correlation coefficient, it shows that  since borrowers with more monthly income could loan more money.

it is noticed that Employed people can get larger loan amounts compared to all other categories.

The loan amount increases with better creditscore. The borrower APR decreases with better score. Interestingly, the relationship between borrower APR and loan amount turns from negative to slightly positive .


## Key Insights for Presentation
For the presentation, I focus on just the influence of some variables on interest rate and loan. I started by introducing the loan status and loan amount variable, by plotting their distribution.

Afterwards, i have used violin plots and box plots to dig deeper on the relationship between my variables of interest (interest rate and loan) and the explicative variables.

