# ATM Interface in Java

Welcome to the ATM Interface project in Java! This console-based application allows users to perform various banking operations, including transaction history tracking, withdrawals, deposits, fund transfers, and more.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Database Setup](#database-setup)
  - [Running the Atm Interface](#running-the-atm-interface)
- [Usage](#usage)
- [Contribution](#contribution)

---


## Project Overview

This project is a console-based ATM interface implemented in Java. It consists of five different classes to manage different aspects of the application:

- `ATM`: The main class that handles user interactions and menu options.
- `UserAccount`: Manages user account information, such as User ID, User PIN, and Available Balance.
- `TransactionHistory`: Keeps a record of user transactions, including transaction type, amount, and available balance.
- `DatabaseManager`: Handles database connections and SQL operations.
- `InputHelper`: Provides utility methods for user input validation and formatting.

## Features

- User Account Management: Create and manage user accounts with User ID, User PIN, and Available Balance.
- Transaction History: Keep track of transaction history, including transaction type (withdrawal, deposit, transfer), transaction amount, and available balance.
- Withdrawals: Users can withdraw funds from their account.
- Deposits: Users can deposit funds into their account.
- Fund Transfers: Users can transfer money between accounts.
- Quit: Exit the ATM interface.

## Setup

### Prerequisites

Before running the ATM Interface, make sure you have the following prerequisites installed:

- Java Development Kit (JDK)
- MySQL Database

### Database Setup

1. Create a MySQL database named `atm_interface`.
2. Create two tables:
   - `userAccount` table with columns: `userID` (INT), `userPIN` (INT), and `availableBalance` (DOUBLE).
   - `transactionHistory` table with columns: `userID` (INT), `transactionType` (VARCHAR), `amount` (DOUBLE), and `availableBalance` (DOUBLE).

### Running the ATM Interface

1. Clone this repository to your local machine.
2. Open the project in your preferred Java IDE.
3. Configure the database connection in the `DatabaseManager` class by updating the database URL, username, and password.
4. Build and run the `ATM` class to start the ATM Interface.

## Usage

- When you run the ATM Interface, you will be prompted to log in with your User ID and PIN.
- After logging in, you can select from various banking operations.
- Transactions and account details will be stored in the database for future reference.
- Use the "Quit" option to exit the ATM Interface.

## Contribution

Contributions to the Railway Reservation Systen are welcome! You can contribute by:

- Adding new features or enhancements.
- Fixing bugs and issues.
- Improving code quality and documentation.
  
Thank you for using the ATM Interface in Java!
