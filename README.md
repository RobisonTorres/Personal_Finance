# Personal Budget

## A simple Excel spreadsheet to help control personal finance.

I created this spreadsheet to improve my financial organization, establish a financial plan, and monitor where my money was going. My goal was to make it simple and user-friendly, with each financial transaction entered on a single line, ***automatically updating*** all related sheets.

<br>

![Image](https://github.com/user-attachments/assets/3714527b-8185-4038-b30c-48293db23948)
Balance & Tracking Sheet.

## Features

This Personal Budget is composed of six different sheets, each addressing different aspects:

1. Data Validation - Sets the names of categories.
2. Balance & Tracking - Records all financial operations.
3. Net Salary - Stores all the values related to Income, Deductions, and Investments, divided by months.
4. Expenses - Stores all the values related to Expenses, categorized and divided by months.
5. Dashboard - Shows relevant information for the entire year.
6. Analysis - Based on the description given of each financial operation, some analysis is shown.

## Download

To download and edit the spreadsheet, click on one of its versions (e.g., 'Personal Budget - English.xlsx') and then select 'View raw.' Once the spreadsheet is downloaded, open the file and click 'Enable Editing.'

## Usage

This spreadsheet is designed to help you easily track your income and expenses.

### 1 - Setting Up (Data Validation Sheet):

- Open the Excel Personal Budget file and navigate to the sheet named "Data Validation."
- In this sheet, set the initial balance you have in each account, and customize the category names according to your spending habits. Important: Once you've set your categories and initial balance, avoid changing them later to prevent errors in the calculations.

### 2 - Tracking Financial Operation (Balance & Tracking Sheet):

Go to the "Balance & Tracking" sheet. This sheet consists of tables and a graph that are all automatically updated based on the information you enter in the Tracking table.

### 2.1 - Monthly Summary Table:

* In cell B2, the month name will automatically update based on the date put in cell C7.
* Below, you'll find information for that specific month, including:
    * Balance: This is automatically calculated by subtracting expenses from income and then adding the balance carried over from the previous month.
    * Expenses for the month.
    * Net Salary - Toggle in B4.

### 2.2 - Expenses & Net Salary Graph:

* This graph visually represents your expenses and net salary for the chosen month (selected in B2).
* You can toggle between viewing expenses or net salary by changing the selection in cell B4.
        
### 2.3 - Account Table:

* This table provides an overview of your different accounts (e.g., banking account, savings, debt, credit card).
* In cell C7, you can select a date to view the account balance for that specific day. By default, the current date (or =TODAY() in Excel) will be used if the cell is left blank.
* When you record a credit card purchase in the Tracking table, cell C13 will change color to indicate a payment is due. To make a payment, select 'Payment' and choose 'Credit Card' under 'Operation.' This also applies to the Debt account.

### 2.4 - Tracking Table:

* This is the heart of the spreadsheet. Here, you'll record your financial operation by selecting the appropriate category and entering the amount.
* Any entry you add in this table automatically updates the other tables and graphs on the "Balance & Tracking" sheet and in the other sheets as well.
* Tip  - By pressing the 'Tab' key, you can easily switch between fields and create a new row at the end of the table.

## Note 

***Important***: The date of an operation affects the Accounts and Monthly Balance differently. Operations dated in the future impact only the Monthly Balance for the current month. Operations dated today or earlier affect both Accounts and Monthly Balance. When the values of Accounts and Monthly Balance match, cell C3 will turn green to indicate alignment; otherwise, it will turn orange.

## Tips 

You can create a financial plan by adding operations dated in the future. For example, include financial operations that you know will occur in the coming months (such as salary, bills, trips, and deductions). This way, you can spend your money more wisely.      

***For better visualization adjust the zoom and press "Ctrl+F1" for hide the commands.***