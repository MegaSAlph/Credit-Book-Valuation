# Credit-Book-Valuation
The goal of this task is to fit a statistical model to historical credit data and then use the model to estimate the value of current loans.
The task is completed using a python notebook and a number of commonly-used data science libraries.

1. Install Anaconda and Launch Jupyter Notebook

If you do not already have Anaconda download and install it (https://www.continuum.io/downloads). Launch a Jupyter Notebook (either from Anaconda Navigator if you have it installed or from the terminal or command prompt with the command jupyter notebook).

Download data_science_task.ipynb and data_science_task.csv on 
Import the supplied ipython notebook i.e data_science_task.ipynb into the notebook.
Import the supplied comma-separated data file i.e data_science_task.csv into the notebook.


Each line in the dataset represents a loan. Each loan has the following fields:

account_no - A unique account number per loan
gender - The gender of the account holder - either ‘M’ or ‘F’
age - The age of the account holder at the point of application
income - The monthly nett income of the account holder at the point of application
loan_amount - The amount of money lent
term - The number of months that the loan is to be repaid over
installment_amount - The monthly installment amount
insterest_rate - The interest rate on the loan
credit_score_at_application -The credit score at the point of application, this is a positive integer less than 1000. The higher the score the more creditworthy the applicant is believed to be.
outstanding_balance - The remaining amount of the loan that still has to be repaid
status - This indicates what state the account is in. This field can take one of three values
  “LIVE”: The loan is still being repaid - the field outstanding_balance will be greater than zero.
  “PAID_UP”: The loan has been completely repaid - the field outstanding_balance will be zero.
  “DEFAULT”: The loan was not fully repaid and no further payments can be expected - the field outstanding_balance will be greater than     zero and the amount will not be recoverable.
