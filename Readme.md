## <center> ATM Banking System </center> ##
This project simulates an ATM Banking System using Python and MySQL. The system allows users to perform various banking operations, including account creation, PIN updates, cash withdrawals, deposits, and transaction history checks. The system also integrates email functionality for sending verification codes and transaction notifications.

### Features ###
Create New Account: Allows users to create a new bank account by entering account details.
Update PIN: Users can update their ATM PIN securely.
Withdraw Cash: Users can withdraw money after verifying their identity with an email code.
Deposit Cash: Users can deposit money and receive a confirmation email.
Check Transactions: Users can view their last 10 transactions.
Voice Assistance: Integrates Windows SAPI to provide voice assistance during operations.
Email Notifications: Sends verification codes and transaction details to users via email.

### Technologies Used ###
Python: Application logic and user interface.
MySQL: Database for storing user accounts and transactions.
smtplib: For sending emails.
pywin32 (win32com.client): For voice assistance using Windows SAPI.

### Prerequisites ###
Python 3.x: Install from here.
MySQL: Install and set up a MySQL server. You can download it here.
MySQL Connector: Install the MySQL Connector for Python.
bash
Copy code
pip install mysql-connector-python
pywin32: For voice assistance.
bash
Copy code
pip install pywin32
Installation
Clone the repository:

git clone https://github.com/Piyush-Pandey312/ATM_Banking_System.git

### Configure MySQL Database: ###

Create a database in MySQL.
Import the provided SQL schema to create the necessary tables.
Update the db_host, db_name, db_user, and db_password variables in the script with your database details.
Email Configuration:

Update the sender_email, sender_password, smtp_server, and smtp_port variables with your email account details.
Run the Application:

python atm_banking_system.py

### Usage ###
Launch the application and follow the on-screen instructions.
Choose from the available menu options to perform different banking operations.
Ensure that your MySQL server is running and that you have a stable internet connection for email functionality.
Example Workflow
Create a new account by entering the required details.
Withdraw cash by entering the account number, PIN, and a verification code sent to your email.
Deposit cash and receive a confirmation email with your updated balance.
Check your recent transactions to track your account activity.
Troubleshooting
Database Connection Error: Ensure that MySQL is installed and running. Verify your database credentials.
Email Sending Issues: Ensure that your email credentials are correct and that you have allowed less secure apps to access your email account if using Gmail.
Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

### License ###
This project is licensed under the MIT License - see the LICENSE file for details.