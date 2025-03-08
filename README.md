# COMP-1327 Assignment 4

## Author

Michael Obikwere

## pixell_transaction_report.py

## Description

- My aim is to make sure that the code runs properly and accurate, and 
I will use Exceptions to catch invalid transaction, and display them 
to the users. 
- I will also run through the program using a debuging tool, to make 
sure that there isn't any logic errors, and to modify the program if 
needed, to ensure that the code runs properly as expected.

## Code Modification 1

- Added error handling when the data file is not within the application
 directory.

 ## Code Modification 2
 - Validation 1: I add a logic to check transaction types that are not 
 correct, and rise an invalid transaction type  message for the users.
 - Validation 2: I added an exception to catch transaction amounts that
 are not numeric values, and then display an invalid transaction amount
 message to the users.
 - Collection of Invalid Transactions: I added an else statement that 
 collects all invalid transactions, both transaction type or amount,
 together with the transaction information, and store them in a tuple, 
 and added them to the list of rejected transactions.