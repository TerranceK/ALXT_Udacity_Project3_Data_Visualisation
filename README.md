# Guaging the suitability of different feature for predicting a borrower's Annual Percentage Rate (APR) for a loan
## by TERRANCE KANYEZI


## Preliminary Wrangling

> First, the investigator focused on cleaning the data and making it suitable for analysis.
> This analysis was then conducted in three phases:
> 1. Univariate, 
> 2. Bi-variate and 
> 3. Multivariate analysis.

## Dataset

> The dataset used herein is from Prosper, and contains loan data for 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

> In this project only 16 features will be explore out of the 81 available features.

## Data Assessing and Cleaning

> 1. Select important data columns features to visualize
> 2. Rename the selected columns to a uniform naming casing
> 3. Check for null values 
> 4. Drop null values if they exist
> 5. Drop duplicated rows using the listing key as the Unique Identifier 

## Summary of Findings

> I'm most interested in figuring out what features are best for predicting the borrower's Annual Percentage Rate (APR) for the loan.

> The Borrowers with the largest APR all have a 36 months term.

> the borrower APR decreases with the better rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR. Borrowers with better prosper rating also have lower estimated losses, estimated effective yields and lower borrower rate.

> Most borrowers chose to go for loans with term of 36, while less borrowers chose the 60 term loans while very few borrowers chose the 12months term loan

>There is a interaction between borrowers bpr and Prosper rating features. Proportionally.

> Most loans seem to have an APR of around 0.36%. The least APR values seem to be 0.05%, 0.40% and higher and 0.37%.

## Key Insights for Presentation

> The figure shows that the borrower APR decreases with the better rating. Borrowers with the best Prosper ratings have the lowest APR.
> I finalised the analysis by usig a correlation heatmap to get an overview of the relationships between variables.

## Final Steps

> In the final step, findings from our exploration was taken and then conveyed through exploratory analysis. A slide deck was created to communicate findings easily.
