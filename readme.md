# Prosper Loan Data Analysis

## Data overview 
**I choose to work on prosper Loan data**.
This data set contains 113,937 loans with 81 columns including loan amount, borrower rate (or interest rate), current loan status,borrower income, and many others. I chose only 20 columns that i needed in my analysis.

## Scoop of My analysis 

My analysis based on a senario where I imagining myself as a manager in the prosper company who want to know a bout the company performance for the last period ,So what kind of information he wants to know. 
based on that i formulated my analysis to answer on 7 most importrant Question any manager want to know, Which are:

  **1- Is home owner tend to borrow more than non-home owner?**
  
  **2- Is there any relation between amount of the loan and interest rate?**
  
  **3- Which loan category has the heighest amount of loans?**

  **4- Is there any effect of season on loans amounts?**

  **5- What is factors have most effect on the default on a loan (loan status , APR or monthly payments...)?**

  **6- What is the factors that affect most on estimated return?**

  **7- Is there in differenc on interest rate between student loan and non-students loan?**

### My findings:
 **Question-1 Answer** : I found that there is no difference between homeowners and non- homeowners in amounts of loans so both have the same tendency to borrow.

**Question-2 Answer** : there is a negative relation between loan amount and interest rate mean that with increasing loan amount the interest rate decreased.

**Question-3 Answer** : I found that the dept consolidation is the heighest loans amounts among other category

**Question-4 Answer** : The data shows that each popular loan amount has a peak of increase rate in specific Quarter:
- **loans amounts from 3000 to 5000 increased during Qurter 3 (June, AUG, SEP)**
- **loans amounts at 10000 increased during Qurter 4 ( OCT, NOV, DEC)**
- **loans amounts at 15000 quarter 1 (JAN, FEB, MAR)**

**Question_5 Answer** : I found that long loan terms (36 and 60) and monthly payments less than 1000 dollars are more risk to be defaulted, so Lenders should are advised to keep terms shorter terms (12 months) and monthly payments above 1000 dollars and APR less than or equal 40% to avoid defaulting loans.

**Question_6 Answer** : I discover that that higherloan terms (36 and 60 months) are associated with higher estimated return but also with a higher risks of being defaulted or chargedoff ,SO if you are an invistor the best advise would be to invest in loans with repeated small terms(12) and lower revenue rather than long terms loan with high revenue and this confirme the previous point.

**Question_7 Answer** : The data shows no difference in interest rates between students and non-students loans

## Key Insights for Presentation

In my Presentation, I tried to make my audience familiar with the data and make sense of numbers range for each numeric variable and counts for each categorical variables.Then i show the charts that answers my questions directly using a wide range of charts. And to prove my points i started from showing one to one relation then adding variables gradually to reach my conclusions.
I focused specially on effect of Loans terms ,loans amounts ,borrower APR, interest rate and estimated return. and then compairing them against categorical variables a need such as defaulted and non-defaulted loans ,students and non-students loans.

## references :
1-matplotlib documentations :https://matplotlib.org/stable/contents.html
2-seaborn documentations :https://seaborn.pydata.org/index.html
3-https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html

