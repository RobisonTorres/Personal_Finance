# Personal Budget

## A simple Excel spreadsheet to help control personal finance.

I decided to create this spreadsheet because I had no financial organization. Every month, I could barely pay my bills, and I didn't know where my money was going.

## Features

This Personal Budget is composed of seven different sheets, each addressing different aspects:

1. Data Validation - Sets the names of categories.
2. Balance & Tracking - Records all financial operations.
3. Net Salary - Stores all the values related to Income, Deductions, and Investments, divided by months.
4. Expenses - Stores all the values related to Expenses, categorized and divided by months.
5. Graphic Categories - Dynamic graphical representation of different categories.
6. Goals - Sets the financial goals to be achieved and their progress. 
7. Graphic Annual - Dashboard of all relevant information for the entire year.

## Usage

Using this spreadsheet is very straightforward:

1. Open the Excel Personal Budget file.
2. Navigate to the sheet "Data Validation" and set the names of the categories to your preference, once set don't change it anymore to avoid errors. Then go to "Balance & Tracking".
3. The "Balance & Tracking" sheet is composed of there tables and one graphic, all of them are connected:

    * The first table is organized by month. Select the desired month in cell B2, and below, you'll find information on Expenses, Expense to Income ratio, and Balance for that month. The Balance in C5 is calculated by subtracting Expenses from your Income and then adding the Balance from the previous month. January's balance reflects your overall starting point and doesn't include previous months' balance. In cell C6, it displays the balance for the entire year, regardless of the chosen month.
    
    * The graphic shows information about expenses and net salary related to the month select in B2. The graphic can be toggled by selecting the option in cell B3.

    * The Account table provides information about different accounts and their current values. However, the Credit Card account in cell C13 behaves differently due to its two-day cycle. A purchase with the credit card will change the color of cell C13, indicating a payment is due. To make a payment, select 'Payment' and choose 'Credit Card' under 'Operation.' This will reset the value in cell C13 to $0.

    * Cell C14 calculates the difference between the total Accounts (C9:C12) and the Balance of the month (B5). This value should be $0, indicating that the sheet aligns with the Accounts.

    * The Tracking table is central to the Personal Budget. Adding a record here automatically updates the tables present in the current sheet and in the other sheets, as well. It's important to note that the date of the operation affects Accounts and the monthly balance differently. Operations dated in the future only affect the current month's balance, while operations dated on or before the current day impact both. That's because future operations don't affect the current Accounts.

    * The table Tracking has seven different columns:

        - Date: Enter the date of the financial operation.
        - Month: Automatically populated with the month name.
        - Operation: Specify the type of operation.
        - Category: Specify the sub-operation (e.g., selecting "Income" in the Operation column allows you to choose a sub-operation like "Salary").
        - Account: Specify where the money will be spent or deposited.
        - Amount: Enter the value of the operation.
        - Description: Provide a brief description of the operation.

* Note: I prefer using only the Balance and Graphic Annual sheets for easier navigation. The other ones are kept hidden and serve as reference. For that reason I will only explain how the "Balance & Tracking" works.        
        
4. For better visualization adjust the zoom and press "Ctrl+F1" for hide the commands.

These steps will help you effectively utilize the features of the spreadsheet to manage your personal finances.