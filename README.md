# (Dataset Exploration Title)
## by (your name here)


## Dataset
> The data consist of information on loans, with two major section; The borrower and Lender information.
The dataset can be found here - https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.
With further documentation to understand the features of the dataset here - https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0

> After selection of the features that are necessary for my analysis, I performed some wrangling operations which includes;
removal of duplicates, dropping of null values, I also filled null values for the borrower apr with the mean value.


## Summary of Findings

> In the exploratory analysis, I found out that there was a positive correlation between the stated monthly income and the employment 
status which ultimately created a positive correlation to with the loan status. That is, those who were employed, receiving monthly 
income, had higher percentage of loan status as completed and paid. To make analysis clearer, I had to limit the values of the loan 
status to Completed, Current, Charged Off and Defaulted. 

> Also, I saw that a large percentage of the borrowers (over 70%) had loan term of 36months. Ialso noticed that the stated monthly
income had a negative correlation with the loan original amount and stated monthly income with higher values had loan terms of 12 monthly, 
a good amount of which defaulted.

> Outside the main findings, I checked out the occupation distribution of the loan takers and I was a bit disappointed that the largest 
value was "other", making it impossible to do a proper correlation with the employment status.


## Key Insights for Presentation

> The presentation was focused on the influence of the other features which are borrower apr, stated monthly income, employment status, 
term and loan original amount on the loan status. The presentation started with the comparism between the distribution stated monthly 
income and loan original amount, followed by the distribution of the employment status and loan terms.

> Next, I looked at the loan status across the three terms (12months, 36months and 60months) and a comparism to solidify the relationship 
between the stated monthly income and employment status as regards the loan status. I made sure to use varying yet consist colors in my 
plots to ensure the information is clearly understood by any reader.#   P r o s p e r - L o a n - - - U d a c i t y - P r o j e c t  
 