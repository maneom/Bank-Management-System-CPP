## Bank Management System
This Bank Management System is implemented in C++ and allows users to perform various banking operations. Here's an overview of its key features and functionality:

__Class Definition (bank_holder)__: Defines a class to store details of a bank account holder, including name, address, phone number, date of birth, Aadhar number, account number, balance, password, loan amount, fixed deposit, and return loan.

__Constructor__: Initializes the account balance, loan amount, fixed deposit, and return loan to zero.

__Member Functions__:
create_acc(): Allows the user to create a new account by entering personal details and setting a password.
acc_holder_details(): Displays the account holder's details after verifying the password.
deposit(): Allows the user to deposit money into their account and updates the balance.
withdrawal(): Allows the user to withdraw money from their account, provided they have sufficient balance.
balance_enq(): Displays the current balance and calculates the interest (5% per year).
prt_passbook(): Prints the transaction history from a file (BANK_HOLDER_DETAILS.txt).
easy_loan(): Allows the user to apply for a car loan or a home loan with respective interest rates.
return_loan(): Allows the user to repay their loan partially or completely.
fixed_deposit(): Allows the user to create a fixed deposit for 5 or 10 years with corresponding interest rates.
Update Account Details:
update_acc(): Allows the user to update their name, phone number, address, or date of birth.

__Delete Account__:
delete_acc(): Allows the user to delete their account after verifying the password.

__File Handling__:
Uses file handling (ofstream and ifstream) to store and retrieve transaction details in a text file (BANK_HOLDER_DETAILS.txt).

__Main Function__:
Displays a welcome message and a menu for various banking operations.
Uses a do-while loop to continuously prompt the user for input until they choose to exit.

__Overall, this Bank Management System provides a basic framework for managing bank accounts, transactions, loans, and fixed deposits.__
