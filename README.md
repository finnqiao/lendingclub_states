# lendingclub_states

Variables from Lending Club data:

loan_amnt - The listed amount of the loan applied for by the borrower. If at some point in time, the credit department reduces the loan amount, then it will be reflected in this value.  <br />
funded_amnt - The total amount committed to that loan at that point in time.
term - The number of payments on the loan. Values are in months and can be either 36 or 60.
int_rate - Interest Rate on the loan
grade - LC assigned loan grade
emp_length - Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years.
home_ownership - The home ownership status provided by the borrower during registration. Our values are: RENT, OWN, MORTGAGE, OTHER.
annual_inc - The self-reported annual income provided by the borrower during registration.
title - The loan title provided by the borrower
addr_state - The state provided by the borrower in the loan application
dti - A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LC loan, divided by the borrower’s self-reported monthly income.
open_acc - The number of open credit lines in the borrower's credit file.
total_acc - The total number of credit lines currently in the borrower's credit file
pub_rec - Number of derogatory public records
