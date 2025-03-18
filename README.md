# ATM Console-Based System

## Overview
This is a simple ATM (Automated Teller Machine) system implemented in Python. The program allows users to perform basic banking operations such as withdrawal, deposit, PIN generation, mini-statement retrieval, and PIN reset.

## Features
- Withdrawal
- Deposit
- PIN Generation
- Mini Statement
- PIN Reset

## Prerequisites
- Python 3.x installed on your system

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/atm-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd atm-system
   ```
3. Run the program:
   ```bash
   python atm.py
   ```

## Usage
When you run the program, it will display a menu with the following options:
1. Withdrawal
2. Deposit
3. PIN Generation
4. Mini Statement
5. Reset PIN
6. Exit

### Withdrawal
- Enter your account number.
- Provide your PIN.
- Specify the amount to withdraw.
- If the balance is sufficient, the withdrawal is successful.

### Deposit
- Enter your account number.
- Enter the amount to deposit.
- The balance is updated accordingly.

### PIN Generation
- Enter your account number.
- Set up a new PIN if not already set.
- Confirm the PIN.

### Mini Statement
- Enter your account number and PIN.
- Displays account details, including name, account number, date of birth, and balance.

### Reset PIN
- Enter your account number.
- Provide your old PIN.
- Set a new PIN and confirm it.

### Exit
- Exits the program.

