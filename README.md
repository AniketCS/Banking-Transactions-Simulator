# Banking-Transactions-Simulator
Banking Transactions Simulator is a Java-based project that simulates banking transactions for checking and credit accounts. It allows the creation of accounts, deposits, and withdrawals, and tracks the balance or credit of each account after applying transactions.  
The program will read the account information from Accounts.txt, apply transactions from Transactions.txt, and display the final balances of specific accounts.
Project Structure


# The project is organized into different folders:
-Constants: Contains Java enumerations for account types (AccountType) and transaction types (Transaction).

-Data: Contains the text files Accounts.txt and Transactions.txt, which hold the initial account information and transactions, respectively.

-Pojo: Contains the Plain Old Java Objects (POJOs) representing the account classes (Account, Checking, Credit).

-Repository: Contains the AccountRepository class, which provides an in-memory repository for storing and managing account objects.

-Service: Contains the service classes CheckingService and CreditService, which implement the AccountService interface to provide account-related operations.


# Adding New Accounts and Transactions
To add new accounts, modify the Accounts.txt file by following the format: ACCOUNT_TYPE ACCOUNT_ID BALANCE_OR_CREDIT.

To add new transactions, modify the Transactions.txt file by following the format: ACCOUNT_TYPE ACCOUNT_ID TRANSACTION_TYPE AMOUNT.

Please note that account IDs should be unique, and transaction amounts should be positive values for deposits and negative values for withdrawals.
