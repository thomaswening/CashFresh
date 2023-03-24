# CashFresh

"CashFresh" is an open-source personal finance app for tracking expenses and income, creating savings plans and managing repayments.

## Table of Contents


## Overview

"CashFresh" is currently in its planning stage. This project aims to create a personal finance app that allows users to track their income and expenses, create and manage savings plans, and manage their repayments. The app will be designed with ease of use and simplicity in mind, while providing powerful tools to help users manage their finances effectively. 

## Features

I am looking to develop a personal finance application that automates the calculations and input procedures of my household sheet on Google Sheets. The app should have a user-friendly interface, and it will include the following key features:

- Bookkeeping: The user be able to input expenses and income with the relevant financial data.

- Accounting: The app should reflect banking accounts and the money flows between them.

- Monthly Overview: The app should calculate a monthly budget, including how much money the user must save each month for payments with a cycle greater than one month.

- Savings Plan Feature: The user will be able to create a savings plan that calculates how much money they need to save each month to achieve a target amount in a given number of months, or vice versa. The app will display the new monthly budget for the given scenario.

- Savings Compliance Feature: The user will be able to input their current savings account balance and compare it to the sum of their savings plan and the savings amount for payments with a cycle greater than a month to assess whether they are in compliance.

- Credit Repayment Planning Feature: The user will be able to plan the repayment of their consumer credit using this app. The app will be able to calculate the credit period given a fixed installment rate or the installment rate needed to achieve a given credit period. It will also calculate the total paid interest, current interest amount and redemption amount, the amount of the last payment, and the new budget with the given scenario. The app will be able to compare a given scenario with a new one and calculate the differences in total paid interest and credit period.

- Payment Calendar: There will be a calendar for payments with cycles greater than a month. I also want to be able to export this calendar, specifically to Google Calendar.

- Backup: The user will be able to create a backup, specifically on their Google Drive.\

## Main User Tasks

These are the main tasks that the user might want to accomplish.

- view monthly overview
- create, edit, delete income/expense items (transactions)
- create, edit, delete accounts
- view the cash flow between the accounts
- create, edit, delete savings plans
- check compliance for savings plan
- update savings account balance
- create, edit, delete credit repayment plans
- view payment calendar
- export payment calendar
- creating a back-up on Google Drive

### View Monthly Overview
Upon opening the app, the user sees a dashboard that displays their monthly budget together with the total monthly income and total monthly expenses, as well as any upcoming expenses for the next four weeks.

### Transaction Management
The user clicks on the appropriate section of the budget overview (incomes/expenses) and is taken to the "Transactions" section, where all income/expense items are displayed in a table.

#### Creating a Transaction Item
The user clicks on "Add item" in the last, empty row of the table and is taken to an empty detail view. Here, they fill out the necessary values and then save the item.

#### Editing a Transaction Item
The user double-clicks on an existing item in the table to edit it and is taken to its detail view. Here, they can edit the values and then save the item.

#### Deleting a Transaction Item
The user hovers over an item and clicks on the "x" that appears on the right-hand side of the item to delete it.

### Account Management
The user selects the "Accounts" tab and is taken to the "Accounts" section. Here, they are presented with an overview of all accounts and the cash flow between them.

#### Creating an Account
The user clicks on "Add account" and is taken to an empty detail view. Here, they fill out the necessary values and then save the account.

#### Editing an Account
The user double-clicks on an existing account and is taken to its detail view. Here, they can edit the values and then save the item.

#### Deleting an Account
The user hovers over an account and clicks on the "x" that appears on the right-hand side of the account to delete it.

### Savings Plan Management
The user selects the "Savings Plan" tab and is taken to the "Savings Plan" section. Here, they are presented with an overview of the current savings plan if there is one.

#### Creating a Savings Plan
The user fills out the form. As soon as all the necessary fields are filled, they are presented with the resulting new budget. The user then saves the plan.

#### Editing a Savings Plan
The user changes the fields they want to change and is presented with the change (absolut and relative) of the parameters and the resulting new budget. The user then proceeds to save the new plan.

#### Deleting a Savings Plan
The user clicks on the "x" (where?) to delete the savings plan.

#### Check Compliance with Savings Plan
The user clicks on "Check compliance" and is then prompted to fill in their savings account balance. The app then calculates how much money should be on it, given the recurring expenses and the savings plan. If the balance is less than that amount, the user is informed that they are not in compliance with their plan. Otherwise, they are told that they are in compliance. Either way, the difference or surplus is displayed.

### Credit Repayment Plan Management
The user selects the "Credit Repayment Plan" tab and is taken to the "Credit Repayment Plan" section. Here, they are presented with an overview of the current repayment plan if there is one.

#### Creating a Credit Repayment Plan Management
The user fills out the form. As soon as all the necessary fields are filled, they are presented with the resulting new budget. The user then saves the plan.

#### Editing a Credit Repayment Plan Management
The user changes the fields they want to change and is presented with the change (absolut and relative) of the parameters and the resulting new budget. The user then proceeds to save the new repayment plan.

#### Deleting a Credit Repayment Plan Management
The user clicks on the "x" (where?) to delete the repayment plan.

### Payment Calendar
#### Viewing the Payment Calendar
The user clicks on the tab "Payment Calendar" and is taken to the "Payment Calendar" section where they are presented with a calendar containing all the recurring payments.

#### Exporting the Payment Calendar
The user clicks on "Export Payment Calendar" and then chooses where to export the calendar to in a pop-up window. Upon choosing the destination directory, they click on "Confirm" and the calendar is exported to that path.

### Making a Back-Up to Google Drive
The user clicks on "Back-up data to Google Drive". If they have not authenticated themselves before, they will be presented with an authentication pop-up and then the back-up proceeds. Otherwise, it proceeds right away. The user is presented with a success/error message.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the [LICENSE.md](LICENSE.md) file for details.
