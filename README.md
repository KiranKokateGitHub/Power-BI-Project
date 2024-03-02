Problem statement:

**Banking

Case Study: Unlocking Financial Insights in Banking Data**

**Background**
As a data analyst at FinInsight Group, a consultancy specializing in banking analytics, you are equipped with two comprehensive datasets: 'Banking Transactions' and 'Customer Account Details'. The 'Banking Transactions' dataset records detailed transaction data, including types, amounts, dates, and branch information. The 'Customer Account Details' dataset provides insights into account holders, covering account types, balances, interest rates, credit scores, and loan amounts. Your expertise is crucial in a sector where financial data drives strategic decisions in customer relationship management, risk assessment, and product offerings.

**Objective**
Your mission is to utilize Tableau's robust capabilities to craft a compelling narrative from the provided datasets. This task will encompass thorough data preparation, intelligent data modeling, and the skillful application of calculated fields and Tableau functions for sophisticated analysis. The ultimate aim is to construct an interactive and intuitive dashboard in Tableau that showcases your key discoveries, offering concise, actionable insights into the optimization of hotel operations and performance.

**Data Source:

BankingDataset1.xlsx**
The "BankingDataset1.xlsx" file contains the following columns:
1.	TransactionID: A unique identifier for each transaction.
2.	AccountNumber: The account number associated with the transaction. (Foreign Key)
3.	TransactionType: The type of transaction (e.g., Transfer, Deposit, Withdrawal, Payment).
4.	Amount: The amount of money involved in the transaction.
5.	TransactionDate: The date when the transaction occurred.
6.	BranchCode: The code of the bank branch where the transaction took place.
7.	Currency: The currency in which the transaction was made.
8.	TransactionTime: The time of day when the transaction occurred (in hours).
9.	
**BankingDataset2.xlsx**

The "BankingDataset2.xlsx" file contains the following columns:
1.	AccountNumber: A unique identifier for each account, corresponding to 'AccountNumber' in "BankingDataset1.xlsx". (Primary Key)
2.	AccountHolder: The name of the account holder.
3.	AccountType: The type of account (e.g., Credit, Loan, Checking).
4.	Balance: The current balance of the account.
5.	InterestRate: The interest rate applicable to the account.
6.	CreditScore: The credit score of the account holder.
7.	OpeningDate: The date when the account was opened.
8.	LoanAmount: The amount of loan associated with the account (if applicable).
9.	AccountHolderDetails: Details about account holders - employment sector, years at current residence, and city of residence etc.
10.	
**Part 1:**
 Data Cleaning, Modeling, and Advanced Analysis in Tableau
**1.	Data Preparation **
   	
o	Import both datasets into Tableau. Perform a preliminary examination of the data. Identify any data quality issues or inconsistencies.
o	Clean and prepare the data if necessary (e.g., handling missing values, data type conversions).

**2.	Calculated Fields:** Create a calculated field to find the 'Age of Account' in days from the 'OpeningDate' till the current date.

**3.	Hierarchy Creation:** Create a hierarchy in BankingDataset1 for 'TransactionDate', 'TransactionTime'. How does this hierarchy enhance your analysis?

**4.	Grouping Data:** Create a group in BankingDataset2 based on 'CreditScore' (e.g., low, medium, high). Define the ranges for these groups.

**5.	Discretize a Continuous Variable:** Convert 'Balance' from a continuous to a categorical variable (e.g., Low, Medium, High balances). Define the thresholds for these categories.

**6.	Splitting Data:** Split the 'AccountHolderDetails' into multiple columns. What insights can you extract from this newly formatted data?
7.	**Time-Series Analysis:** Analyze the trend of transaction amounts over time. Does any particular month or quarter show higher transaction volumes?

**8.	Correlation Analysis:** Is there a correlation between 'Balance' and 'CreditScore' in BankingDataset2? Visualize and interpret the results.

**9.	Aggregate Functions: **Calculate the average transaction amount for each type of transaction. What does this tell you about customer behavior?

**10.	Filtering Data:** Create filters to view transactions only for specific branches. Which branch has the highest number of transactions?

11.	Parameter Control: Add a parameter control to switch between different account types in BankingDataset2. What insights does this provide?

12.	Top N Analysis: Identify the top 10 customers with the highest balances. Display their names and account details.

13.	Conditional Formatting: Apply conditional formatting to highlight accounts in BankingDataset2 that have a balance greater than a specified parameter value.

14.	LOD Expressions: Use a Level of Detail expression to find the average balance per account type. How does this differ from a simple average?

15.	Trend Lines: Add trend lines to your time-series analysis. What prediction can you make for future transaction volumes?

16.	Set Analysis: Create a set of accounts in BankingDataset2 that have a loan amount greater than their balance. What proportion of accounts does this represent?

17.	Custom Date Fields: Create a custom date field in BankingDataset1 that combines 'TransactionDate' and 'TransactionTime' into a single datetime field. Use this field to analyze transaction patterns throughout the day.

18.	Advanced Data Calculations: Create a complex calculated field in BankingDataset2 that categorizes accounts into risk categories based on a combination of 'Balance', 'CreditScore', and 'LoanAmount'. Define the logic for categorization and analyze the distribution of accounts across these risk categories.

19.	Predictive Analysis: Using a trend line in Tableau, predict future balances for accounts in BankingDataset2. Discuss the reliability of these predictions based on the available data.

20.	Cluster Analysis: Utilize Tableau’s clustering feature to group transactions in BankingDataset1 based on amount, type, and time. Analyze the characteristics of each cluster and hypothesize what each might represent in terms of customer behavior.

21.	Market Basket Analysis: Conduct a market basket analysis to find associations between different transaction types in BankingDataset1. For instance, discover if certain types of transactions frequently occur together, suggesting a pattern in customer behavior.
(Note: Show Vizualizations wherever possible in Part 1)

**Part 2: Dashboard Building**

**1.	Comprehensive Banking Dashboard **
o	Create a dashboard in Tableau showcasing key metrics such as transaction volumes, account balances, loan amounts, and credit scores. Include filters for account types, branches, and currencies.

**2.	Dashboard Design and Functionality **
o	Focus on the dashboard's design and functionality. Ensure it is user-friendly, visually appealing, and provides interactive elements.

**3.	Time-Based Analysis in Dashboard **
o	Incorporate time-based analysis in your dashboard, such as trends in account opening and transaction patterns over time.

**4.	Interactive Analysis of Loan Data **
o	Create an interactive section for analyzing loan data, including loan amounts, interest rates, and credit scores.

**5.	Visualization of Transaction and Account Data **
o	Implement visualizations that display transaction and account data effectively, providing insights into customer behavior and bank operations.

**6.	Key Insights and Data Storytelling **
o	Provide a section summarizing key insights or stories from the data. Highlight significant findings or trends that emerged from your analysis.

