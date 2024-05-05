# Personal Budget

## A simple Excel spreadsheet to help control personal finance.

I decided to create this spreadsheet because I lacked financial organization, wanted to establish a financial plan, and needed to track where my money was going.

## Features

This Personal Budget is composed of five different sheets, each addressing different aspects:

1. Data Validation - Sets the names of categories.
2. Balance & Tracking - Records all financial operations.
3. Net Salary - Stores all the values related to Income, Deductions, and Investments, divided by months.
4. Expenses - Stores all the values related to Expenses, categorized and divided by months.
5. Dashboard - Shows relevant information for the entire year.

## Download

To download the spreadsheet, click on one of its versions, e.g., "Personal Budget en-us.xlsx", and then click "View raw".

## Usage

This spreadsheet is designed to help you easily track your income and expenses.

### Setting Up (Data Validation Sheet):

- Open the Excel Personal Budget file and navigate to the sheet named "Data Validation."
- In this sheet, set the initial balance you have in each account, and customize the category names according to your spending habits. Important: Once you've set your categories and initial balance, avoid changing them later to prevent errors in the calculations.

<br>

![data](https://github.com/RobisonTorres/Personal_Finance/assets/69907756/604d5e48-f129-4893-a640-86654703e22e)
Data Validation.

### Tracking Financial Operation (Balance & Tracking Sheet):

Go to the "Balance & Tracking" sheet. This sheet consists of tables and a graph that are all ***automatically updated*** based on the information you enter in the Tracking table.

<br>

![Sheet](https://github.com/RobisonTorres/Personal_Finance/assets/69907756/c5acba6f-9b25-4c8e-ba95-9505b9823522)
Balance & Tracking.

### Monthly Summary Table:

* Select your desired month from the dropdown menu in cell B2.
* Below, you'll find information for that specific month, including:
    * Income entered for the month.
    * Total expenses for the month (derived from the Tracking table).
    * Balance: This is automatically calculated by subtracting expenses from income and then adding the balance carried over from the previous month.

### Expenses & Net Salary Graph:

* This graph visually represents your expenses and net salary for the chosen month (selected in B2).
* You can toggle between viewing expenses or net salary by changing the selection in cell B3.
        
### Account Table:

* This table provides an overview of your different accounts (e.g., banking account, savings, credit card).
* When you record a credit card purchase in the Tracking table, cell C13 will change color to indicate a payment is due (to make a payment, select 'Payment' and choose 'Credit Card' under 'Operation').
* Cell C14 should ideally show a value of $0, signifying that your accounts are reconciled with the spreadsheet.

### Tracking Table:

* This is the heart of the spreadsheet. Here, you'll record your financial operation by selecting the appropriate category and entering the amount.
* Any entry you add in this table automatically updates the other tables and graphs on the "Balance & Tracking" sheet and in the other sheets as well.

Important Note: The date of the operation affects Accounts and the monthly balance differently. Operations dated in the future only affect the current month's balance, while operations dated on or before the current day impact both.

## Note 

I prefer using only the Balance and Graphic Annual sheets for easier navigation. The other ones are kept hidden and serve only as reference, as they receive automatically their values from the table Tracking and shouldn't be changed directly. 

## Tips 

You can create a financial plan by adding operations dated in the future. For example, include financial operations that you know will occur in the coming months (such as salary, bills, trips, and deductions). This way, you can spend your money more wisely.      

For better visualization adjust the zoom and press "Ctrl+F1" for hide the commands.
