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

 ## Code Modification 3

 - Validation 2: I added an exception to catch transaction amounts that
 are not numeric values, and then display an invalid transaction amount
 message to the users.

 ## Code Modification 4

 - Collection of Invalid Transactions: I added an else statement that 
 collects all invalid transactions, both transaction type or amount,
 together with the transaction information, and store them in a tuple, 
 and added them to the list of rejected transactions.

 ## Code Modification 5

 - ZerodivisionError: Added a zerodivision exception to line 155 to 199
 when getting the average of total transaction. 

 ## Code Modification 6

 - noticed that balance is not reflecting the first transaction,
 i change the elif statement to an if statement in line 83.

 ## Code Modification 7

 - Also the Transaction counter was not increasing per valid 
 transaction, so i added a transaction counter increament if the 
 for every valid transaction in line 71.

 ## Code Modification 8

 - Average Transaction Amount was zero because of a logic error in 
 line 79 i fix earlier, but now showing the correct value per valid 
 transaction.

 ## Code Modification 9

 - in line 83, the logic checks if transaction type is Withdrawal
 instead of withdraw, so i modified the code to check if it is
 withdraw.

 ## Code Modification 10
 
 - in line 83, the logic increases customer balance by transaction 
 amount instead of decreasing it, so i corrected the logic error.