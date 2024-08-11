                                                               ATM Interface

Description:

This Java project simulates a basic ATM interface. It allows users to register, log in, and perform
various banking operations such as withdrawing, depositing, transferring money, checking balance, 
and viewing transaction history.

Features
- Registration: Create a new account with a username, password, and account number.
- Login: Securely log in with your username and password.
- Withdraw: Withdraw funds from your account, with balance checks.
- Deposit: Deposit money into your account, with a deposit limit.
- Transfer: Transfer money to another account, with a transfer limit.
- Check Balance: View the current balance in your account.
- Transaction History: View a history of all transactions performed.


Usage

1. Compile the Program
   Open your terminal or command prompt and navigate to the directory containing  `ATMINTERFACE.java`. 
   Compile the program using: javac  ATMINTERFACE.java


2. Run the Program
   Execute the compiled Java program with:   java ATMProject.java

3. Interact with the Program

   - Register: Follow the prompts to create a new account.
   - Login: Enter your username and password to access your account.
   - Withdraw/Deposit/Transfer: Use the menu options to manage your funds.
   - Check Balance/Transaction History: View your current balance and past transactions.


Example Output:

WELCOME TO ATM INTERFACE

1.Register 
2.Exit

Please Enter Your Choice - 1

Enter Your Name : John Doe

Enter Your Username - johndoe

Enter Your Password - password123

Enter Your Account Number - 123456789

Registration completed..kindly login

1.Login 
2.Exit

Enter Your Choice - 1

Enter Your Username - johndoe

Enter Your Password - password123

Login successful!!

WELCOME BACK John Doe 

1.Withdraw 
2.Deposit 
3.Transfer 
4.Check Balance 
5.Transaction History 
6.Exit

Enter Your Choice - 1

Enter amount to withdraw - 500

Withdraw Successfully

1.Withdraw 
2.Deposit 
3.Transfer 
4.Check Balance 
5.Transaction History 
6.Exit

Enter Your Choice - 4

10000.0 Rs

1.Withdraw 
2.Deposit 
3.Transfer 
4.Check Balance 
5.Transaction History 
6.Exit

Enter Your Choice - 6



Notes
- The minimum balance required is 10,000.00 Rs.
- The maximum deposit limit is 10,000.00 Rs.
- The maximum transfer limit is 5,000.00 Rs.
- Ensure you provide valid input to avoid errors.


