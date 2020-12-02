# Prosper Loan Dataset Investigation

## by Bhavin Patel

## Dataset

This dataset (from Prosper) consists of information regarding 113,937 loans including fields like Loan Amount, Borrower Rate, Borrower Income, Borrower Employment Status etc.
The dataset can be found [here] (https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1588505574061000) with additional documentation [here] (https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key=0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE&usp=sharing&sa=D&ust=1588505574062000).
The main objective of this project is to explore the relationships among different variables that may affect the loan status using several visualisation techniques.

## Summary of Findings

<ul>
    <li> Prosper Ratings are normally distributed. Most borrowers have income in the range 50K-75K. Most loans are below 15K with increments in 5K. ProsperRating C is the most frequent rating. </li>
    <li> Long Term Credits (60 Months (in Tenure)) are more expensive than Short Term Credits (12 Months (in Tenure)). Borrower Rate for individuals with Lower Ratings are higher. </li>
    <li> Borrower APR (Annual Percentage Rate) is negatively correlated with major predictors for determining loan status whereas Prosper Ratings are positively correlated.</li>
</ul>


## Key Insights for Presentation

Visuals are created by eliminating chart-junk and using key plots with high data-to-ink ratio for this presentation. The plots convey distribution of various variables using appropriate encodings. BorrowerAPR, ProsperRating, LoanAmounts, Term are all used to convey the story in a compelling manner.
