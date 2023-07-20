# Bank-Management-System
 C++ Project

Introduction:
This is a simple console-based Bank Management System implemented in C++. The project allows users to perform various banking operations, such as creating a new account, depositing and withdrawing funds, checking the account balance, modifying account details, and more.

Features:

Create a New Account: Users can create a new bank account by providing account details such as account number, account holder name, account type (Savings or Current), and initial deposit amount.

Deposit Amount: Account holders can deposit money into their accounts.

Withdraw Amount: Account holders can withdraw money from their accounts.

Balance Enquiry: Users can check the balance of their accounts.

List of All Account Holders: The system can display a list of all account holders with their respective account numbers, names, account types, and balances.

Close an Account: Account holders can close their accounts.

Modify an Account: Users can modify the details of their accounts.

How to Use:

The program's main menu is displayed upon running the application.

To select an option, enter the corresponding number (1-8) and press Enter.

Option 1: Create a new account. Follow the prompts to provide account details.

Option 2: Deposit amount. Enter the account number and the amount to be deposited.

Option 3: Withdraw amount. Enter the account number and the amount to be withdrawn.

Option 4: Balance Enquiry. Enter the account number to check the balance.

Option 5: Display all account holders. Displays a list of all account holders and their details.

Option 6: Close an account. Enter the account number to close the account.

Option 7: Modify an account. Enter the account number to modify account details.

Option 8: Exit the program.

the used functions in the project along with their details:

Functions and Their Details:

void account::create_account()

Description: This function is used to create a new bank account. It prompts the user to enter account details such as account number, account holder name, account type (Savings or Current), and initial deposit amount.
void account::show_account() const

Description: This function displays the details of an account, such as account number, account holder name, account type, and balance.
void account::modify()

Description: This function allows the user to modify the details of an existing account. It prompts the user to enter the new account holder name, account type, and balance.
void account::dep(int x)

Description: This function is used to deposit an amount into an account. It takes the deposit amount as an argument and adds it to the account balance.
void account::draw(int x)

Description: This function is used to withdraw an amount from an account. It takes the withdrawal amount as an argument and subtracts it from the account balance.
void account::report() const

Description: This function displays a formatted report of an account with account number, account holder name, account type, and balance.
int account::retacno() const

Description: This function returns the account number of an account.
int account::retdeposit() const

Description: This function returns the balance amount of an account.
char account::rettype() const

Description: This function returns the account type (Savings or Current) of an account.
void write_account()

Description: This function is used to write (save) the account details to a binary file named "account.dat."
void display_sp(int n)

Description: This function displays the details of a specific account based on the provided account number.
void modify_account(int n)

Description: This function allows the user to modify the details of an existing account. It takes the account number as an argument and updates the corresponding account's information in the file "account.dat."
void delete_account(int n)

Description: This function is used to delete an account based on the provided account number. It removes the account details from the "account.dat" file.
void display_all()

Description: This function displays a list of all account holders along with their respective account numbers, names, account types, and balances.
void deposit_withdraw(int n, int option)

Description: This function allows the user to deposit or withdraw an amount from an account. The option argument is used to differentiate between deposit (option=1) and withdraw (option=2) operations.





