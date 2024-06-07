# Personal_Finance_Analysis_by_Codebasics
![R](https://github.com/MilaarAdedayo/Personal_Finance_Analysis_by_Codebasics/assets/101608507/1e1ed3c2-1ad6-44e8-ae94-f65d0c690b5a)
*I replicated Codebasics's Personal Finance Dashboard project. Here is what I gained*


## Introduction
This is a Power BI project on personal finance analysis which tracks the client's monthly transactions for 37 months (2018-2021).
Dhaval Patel, the client employed the professional services of Hemanand Vadivel a Senior Data Analyst to analyze his finance data between 2018 to 2021.

***Disclaimer*** *The dataset is Codebasics (Dhaval Patel's) Monthly Expenses from 2018 to 2021 and the analysis report was done by Hemanand Vadivel.
The currency in consideration is ₹ - Lakh.*

## Purpose of the Project
1. Learn more about Power BI and data analytics
2. Embed analytics into one's daily life
3. Provide one's data
4. Financial Literacy / Discipline

## Why the Analysis was Performed
To give an idea of how projects are executed in corporate environments.

## Questions of Analysis/Problem Statement
1. What is one's net worth?
2. Is one's spending pattern right?
3. Is one reaching his or her savings target?
4. Which months are financially bad/good?
5. Where or How does one spend?
6. Where or How does one save?

## Technologies Used
Excel and Power BI.

## Data Types and Some Finance Terms
1. Income - Salary, Source 2
2. Savings - Mutual Funds, Emergency Funds, Fixed Deposit, Liquid Cash 
3. Expenses - House Rent, Groceries & Food, Health, Equated Monthly Installments(EMIs), Leisure, Shopping.

## Skills/Concept Demonstrated
The following Power BI features were incorporated:
  - Power Query 
  - Quick Measures 
  - DAX
  - Filters
  - Visuals
  - Tooltips

## Method of Analysis
1. Import Findata from Excel to Power BI
![Excel](https://github.com/MilaarAdedayo/Personal_Finance_Analysis_by_Codebasics/assets/101608507/a888142f-dcd1-4436-841e-6f5fc43e6bfd)
2. Data Transformation performed via Power Query Editor:
  - Unpivot Date - Value column
  - Change type of Date column to 'Date'
  - Change type of value column to 'Fixed Decimal Number'
  - Add Column Year and change type to 'Text'
  - Change date format from 01 January 2018 to Jan 18
  - Close & Apply.
3. Measures created were for:
 - Values / Gross Amount
  - Total Income, Expense & Saving
  - Expense & Savings Percentage
    
   ![Measures](https://github.com/MilaarAdedayo/Personal_Finance_Analysis_by_Codebasics/assets/101608507/8dccfff5-0afe-4b3e-89cf-08029dfdd6b7)
  
  - Income Last Month (LM)
  - Income change Month over Month (MoM) Percentage
  - Savings Target
  - Cumulative Net Worth
4. The Finance Dashboard features 
  - Card visuals showing the KPIs (Net worth, Income, Savings %, Expenses %) and it's Overall KPIs
  - Column charts showing the Expense % and Savings % Breakdowns
  - Table visual showing detailed Statement
  - Slicers showing the timeline selection (years and months)

## Results
_Under the period of consideration_
![Dashboard](https://github.com/MilaarAdedayo/Personal_Finance_Analysis_by_Codebasics/assets/101608507/aedc6413-a40a-45d3-a54c-1a8e3814d280)
- The analysis shows that his total earnings are ₹1.51M and his net worth is ₹325,500.
- House rent (40.44%), Groceries (24.20%), EMIs (21.40%), Health (6.18%), and Leisure (4.10%) are his top 5 spending.
- His monthly savings target of 25% was surpassed 16 times (January to July 2018, October & November 2018, and February to August 2019).
  February & March 2019 were the highest with 32% savings.
- His income changed 5 times, the highest being a 20.51% increase in January 2020.
  In January 2020, his income increased by 20.51% from the previous month which was met by an increase in expenses and 12% savings 
  In December 2019, he incurred the highest expenses (99%) and saved only 1% of his income while February and March 2019 show he saved 32% more than any other month.
  In September 2018, his income increased by 16% from the last month which was met by an 83% expense increase but a decrease in savings.
- 78% of his total earnings go to expenses. The highest spend is his house rent (40.44%), while the least incurred is in leisure (3.68%).
- 22% savings off his total earnings. He saves more in mutual funds (71.58%), while the least of his savings is 0.31% liquid cash.

  **In 2020**
  
  ![2020 Dashboard](https://github.com/MilaarAdedayo/Personal_Finance_Analysis_by_Codebasics/assets/101608507/1d8d3793-2f45-41d3-92f9-1e5b6c8f8e7b)
- ₹593,000 total income, He earned more than the other years but his expenses and savings percentage were 83% and 17% respectively and his net worth is ₹99,000.
- He spent 36.44% on house rent, 25.10% on EMIs, 22.67% on Groceries and the least on shopping (3.74%).
- He saved more in mutual funds (86.77%) and least in liquid cash (-7.07%).

 **In 2019**
 
 ![2019](https://github.com/MilaarAdedayo/Personal_Finance_Analysis_by_Codebasics/assets/101608507/54e04595-05d5-48d6-a7f3-c23916cce035)
- He earned ₹465,000 total income but his expenses and savings percentage were 77% and 23% respectively and his net worth generated is ₹109,000.
- He spent 42.13% on house rent, 25.56% on Groceries, 21.63% on EMIs and the least on shopping (1.40%).
- He saved more in mutual funds (70.64%) and least in liquid cash (3.67%).

**In 2018**

![2018](https://github.com/MilaarAdedayo/Personal_Finance_Analysis_by_Codebasics/assets/101608507/36c28dc8-715d-4979-ad1c-73b40bfe0523)
- He earned ₹392,000 total income, which is the lowest compared to other years but his expenses and savings percentage were 73% and 27% respectively and generated a net worth of ₹105,000.
- He spent 45.91% on house rent, 25.74% on Groceries, 13.91% on EMIS and the least on Health (4.17%).
- He saved more in mutual funds (59.33%) and least in liquid cash (4.31%).

# Conclusion
There is a significant growth in his income while there is a decline in savings over the period in consideration, he shows a consistent habit of saving in mutual funds which increased yearly. There has been a 9.47% reduction in his house rent across three years.

## Knowledge Gained
- Using tooltips to add more information to the UI controls.
- Unlocking more visual formattings.
- How to create and sort the type according to Order No. 
- How to analyse and visualise financial data.

## Associated Finance Terms Meaning
Equated Monthly Installment (EMIs): A fixed payment borrowers make to lenders monthly. One can use them to repay various loans such as mortgages, car loans, and student loans.

