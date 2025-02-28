# atm-simultation
This is a simple Python script that simulates an ATM machine. It allows users to check their balance, withdraw money, deposit money, and exit the system. The script uses the time module to simulate card processing time and includes basic error handling for user input.
The script follows these steps:

Card Insertion Simulation:

The script prompts the user to insert their card and waits for 5 seconds to simulate card processing.

ATM PIN Verification:

The user is asked to enter their ATM PIN (default PIN: 2310).

The script checks if the entered PIN matches the default PIN.

ATM Operations:

If the PIN is correct, the user is presented with the following options in a loop:

Check balance

Withdraw balance

Deposit balance

Exit

Option Details:

Check Balance: Displays the current balance.

Withdraw Balance: Prompts the user to enter an amount to withdraw and updates the balance.

Deposit Balance: Prompts the user to enter an amount to deposit and updates the balance.

Exit: Breaks the loop and ends the script.

Error Handling:

If the user enters an invalid option, the script displays an error message.

If the entered PIN is incorrect, the script prompts the user to try again.

Example Usage
python
