# Lone Data from prosper

## By Muluneh Abrham

## Dataset

In this dataset containing 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

## Tools and Library

[Anaconda distribution](https://www.anaconda.com/products/distribution)

<li>NumPy</li>
<li> pandas</li>
<li>Matplotlib</li>
<li>Seaborn</li>

## Summery of Findings

In the exploration of the dataset, I get the borrower APR is negatively correlated with original loan amount. At different size of the loan amount, the APR has a large range, but the range of APR decrease with the increase of loan amount. The borrower APR also decreases with the increasingly better rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR. Interestingly, the relationship between borrower APR and loan amount turns from negative to slightly positive when the Prosper ratings are increased from HR to A or better.

Outside of the main variables of interest, I found that the loan amount is positively correlated with the stated monthly income, it makes sense since borrowers with more monthly income could loan more money. The loan amount is also increased with the increase of loan term. I also found that borrowers with better ratings have larger monthly income and loan amount. Employed, self-employed and full time borrowers have more monthly income and loan amount than part-time, retired and not employed borrowers. There is a interaction between categorical term and Prosper rating features. Proportionally, there are more 60 month loans on B and C ratings. There is only 36 months loans for HR rating borrowers. For loan amount, there is a interaction between term and rating. With better Prosper rating, the loan amount of all three terms increases, the increase amplitude of loan amount between terms also becomes larger.

## Key Insights for the presentation

For the presentation, I just focus on features that could affect the LoanStatus,borrower APR, and lone origins which are original loan amount, EmploymentStatus. I started by showing the distribution of LoanStatus,borrower APR and loan amount variable. Then, I showed the relationship between borrower APR vs. loan amount, as well as APR vs. EmploymentStatus. I also investigated the effect of EmploymentStatus on relationship between APR and loan amount, as well as the effect of EmploymentStatus on relationship between borrower APR and term.
