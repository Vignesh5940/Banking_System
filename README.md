# Banking_System
Bank Transactions Management System with Doubly Linked List Implementation
This program manages bank transactions using a doubly linked list (DLL) to represent and compute transactions in a bank. It supports various operations such as processing transactions, moving the cursor, inserting transactions, deleting transactions, and retrieving account information.

Data Structures Used:
Doubly Linked List (DLL):

Each node in the DLL represents a transaction.
The cursor denotes the most recent transaction processed.

Singly Linked List (SLL):
Stores the list of bank accounts.
Each element stores the account number and current balance.

Input Format:
The number of accounts (C) to be maintained.
C space-separated unsigned integers denoting account numbers.
The number of transactions (N) to be maintained.
N lines of transactions: Each line specifies a deposit or withdrawal.
Processing directives:
F X: Process the next X transactions after the cursor.
R Y: Undo Y transactions starting from the cursor.
I T K: Insert a new transaction T immediately after the Kth transaction.
D A M: Delete (up to) M transactions of account A after/before the cursor's transaction.
C: Process all transactions after the cursor.
S Y: Print all processed transactions of Account Number Y.
G X: Print count of accounts with balance >= X.
M: Print account number(s) with the highest balance.
V X: Print balance of Account Number X.
The last line contains only the word END.
