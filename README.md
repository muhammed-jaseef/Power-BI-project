# Power BI Project – Banking Transactions & Risk Insights
## 📌Project Overview
This project analyzes banking transactions and customer accounts to identify trends, assess risk, and detect unusual patterns. Using Power BI, the project integrates two datasets (Transactions & Accounts), applies advanced DAX, data transformations, and time-series analysis, and builds an interactive dashboard for financial decision-making.<br>
##🗂️ Data Sources
###📑 Dataset 1: BankingDataset1.xlsx (Transactions Table)
Column	Description
TransactionID	Unique identifier for each transaction.
AccountNumber	Account number linked to transaction (Foreign Key).
TransactionType	Type of transaction (Transfer, Deposit, Withdrawal, Payment).
Amount	Amount involved in transaction.
TransactionDate	Date of transaction.
BranchCode	Code of the bank branch where transaction took place.
Currency	Currency of transaction.
TransactionTime	Time of transaction (in hours).
###📑 Dataset 2: BankingDataset2.xlsx (Accounts Table)
Column	Description
AccountNumber	Unique identifier (Primary Key).
AccountHolder	Name of account holder.
AccountType	Type of account (Credit, Loan, Checking).
Balance	Current account balance.
InterestRate	Interest rate applied to account.
CreditScore	Credit score of account holder.
OpeningDate	Date when account was opened.
LoanAmount	Loan amount associated (if applicable).
AccountHolderDetails	Demographics: employment sector, years at residence, city, etc.


