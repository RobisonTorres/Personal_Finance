# Personal Budget

## A simple Excel spreadsheet to help control personal finance.

I decided to create this spreadsheet because I was having trouble paying my bills. Additionally, the fact that I didn't know where my money was going, always intrigued me.

## Features

This Personal Budget is composed of six different plans, each addressing different aspects:

1. Data Validation - Sets the names of categories.
2. Balance & Tracking - Records all financial operations.
3. Net Salary - Stores all the values related to Income, Deductions, and Investments, divided by months.
4. Expenses - Stores all the values related to Expenses, categorized and divided by months.
5. Graphic Categories - Dynamic graphical representation of different categories.
6. Graphic Annual - Dashboard of all relevant information for the entire year.

* Note: I prefer using only the Balance and Graphic Annual plans for easier navigation. The other ones are kept hidden and serve as reference. For that reason I will only explain how the "Balance & Tracking" works.

## Usage

Using this spreadsheet is very straightforward:

1. Open the Excel Personal Budget file.
2. Navigate to the plan "Data Validation" and set the names of the categories to your preference, once set don't change it anymore to avoid errors. Then go to "Balance & Tracking".
3. The "Balance & Tracking" plan is composed of there tables and one graphic, all of them are connected:

    * The first table is organized by month. Select the desired month in cell B2, and below, you'll find information on Expenses, Expenses/Income ratio, and Balance for that month. Additionally, it displays the balance for the entire year, regardless of the chosen month.
    
    * The graphic shows information about expenses and net salary related to the month select in B2. The graphic can be toggled by selecting the option in cell B3.

    * The Asset table provides information about different assets and their current values. The cell C13 calculates the difference between the total assets C12 and the Balance of the month B5. Ideally, this value should be $0, indicating alignment between the plan and the assets.

    * The Tracking table is central to the Personal Budget. Adding a record here automatically updates the tables present in the current plan and in the other plans, as well. It's important to note that the date of the operation affects assets and the monthly balance differently. Operations dated in the future only affect the current month's balance, while operations dated on or before the current day impact both. That's because future operation don't affect the current assets.

    * The table Tracking has seven different columns:

        - Date: Enter the date of the financial operation.
        - Month: Automatically populated with the month name.
        - Operation: Specify the type of operation.
        - Category: Specify the sub-operation (e.g., selecting "Income" in the Operation column allows you to choose a sub-operation like "Salary").
        - Allocation: Specify where the money will be spent or deposited.
        - Amount: Enter the value of the operation.
        - Description: Provide a brief description of the operation.
        
4. For better visualization adjust the zoom and press "Ctrl+F1" for hide the commands.

These steps will help you effectively utilize the features of the spreadsheet to manage your personal finances.