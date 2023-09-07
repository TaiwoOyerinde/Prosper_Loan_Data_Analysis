# The Prosper Loan Data Exploration
## by Taiwo Oyerinde


## Dataset

The dataset explored for this project was provided in the Udacity Classroom [here]("https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000"). It contains 113,937 loans with 81 variables on each loan listing, which can be summarized into 2: Borrowers' Data and Loan index.
    Before exploring the data, I made a subset of the original data which includes 20 variables of interest among which are: 
- **EmploymentStatus**: The employment status of the borrower at the time they posted the listing.
- **Occupation**: The Occupation selected by the Borrower at the time they created the listing.
- **ListingCategory**: The category of the listing that the borrower selected when posting their listing: 0 - Not Available, 1 - Debt Consolidation, 2 - Home Improvement, 3 - Business, 4 - Personal Loan, 5 - Student Use, 6 - Auto, 7- Other, 8 - Baby&Adoption, 9 - Boat, 10 - Cosmetic Procedure, 11 - Engagement Ring, 12 - Green Loans, 13 - Household Expenses, 14 - Large Purchases, 15 - Medical/Dental, 16 - Motorcycle, 17 - RV, 18 - Taxes, 19 - Vacation, 20 - Wedding Loans
- **LoanStatus**: The current status of the loan: Cancelled,  Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, PastDue. The PastDue status will be accompanied by a delinquency bucket.
- **LoanOriginalAmount**: The origination amount of the loan.
- **Term**: The length of the loan expressed in months.



## Summary of Findings

While exploring, I discovered that **most borrowers were employed and full time in professional fields**. The data also revealed that amongst a list of reasons for taking loans, majority of the people take loans to **consolidate debt, home improvement and for business**. Exploring further, I discovered that there is a strong positive correlation between monthly loan payment and stated monthly income. This was confirmed with the finding that most borrowers have verifiable income sources.
   
It was also note-worthy from the data to realize that majority of the borrowers have a debt-to-income ratio that is less than 1. This means that **their income can optimally suffice their debts**. I also discovered a quite irregular finding that **more non-homeowners completed their loans that homeowners**.
     
Finally, it was satisfying to see from the data that **the higher the loan amount a borrower takes, the longer the term for loan repayment.**


## Key Insights for Presentation

   For my presentation, I focused mainly on:
- the type of borrowers the Prosper loan data contains
- factors that made them eligible for the loan by comparing variables of interest
- and their tendency to repay in terms of loan repayment time, home ownership status and others.
