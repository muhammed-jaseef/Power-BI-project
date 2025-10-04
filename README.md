# Power BI Project – Banking Transactions & Risk Insights
## 📌Project Overview
This project analyzes banking transactions and customer accounts to identify trends, assess risk, and detect unusual patterns. Using Power BI, the project integrates two datasets (Transactions & Accounts), applies advanced DAX, data transformations, and time-series analysis, and builds an interactive dashboard for financial decision-making.<br>
## 🗂️Data Sources
### 📑Dataset 1: BankingDataset1.xlsx (Transactions Table)
Column	Description<br>
TransactionID:	Unique identifier for each transaction.<br>
AccountNumber:	Account number linked to transaction (Foreign Key).<br>
TransactionType:	Type of transaction (Transfer, Deposit, Withdrawal, Payment).<br>
Amount:	Amount involved in transaction.<br>
TransactionDate:	Date of transaction.<br>
BranchCode:	Code of the bank branch where transaction took place.<br>
Currency:	Currency of transaction.<br>
TransactionTime:	Time of transaction (in hours).<br>
### 📑Dataset 2: BankingDataset2.xlsx (Accounts Table)
Column	Description<br>
AccountNumber: Unique identifier (Primary Key).<br>
AccountHolder:	Name of account holder.<br>
AccountType:	Type of account (Credit, Loan, Checking).<br>
Balance: Current account balance.<br>
InterestRate:	Interest rate applied to account.<br>
CreditScore:	Credit score of account holder.<br>
OpeningDate:	Date when account was opened.<br>
LoanAmount:	Loan amount associated (if applicable).<br>
AccountHolderDetails: employment sector, years at residence, city, etc.<br>
##⚙️ Data Modeling & Cleaning
-Performed data cleaning by removing null values, correcting data types, and splitting the AccountHolderDetails column into separate fields such as Employment Sector, Years at Current Residence, and City of Residence.
-Established a one-to-many relationship between Accounts (Dataset2) and Transactions (Dataset1) using AccountNumber.
-Created a calendar table linking Date1 and Date2 for both tables to enable time-based analysis.
-Built fact (Transactions) and dimension (Accounts) tables, along with calculated columns and DAX measures for KPIs and advanced analytics.


