# Accounting Module

This page shows the Accounting module setup and workflows in Odoo for HomeCraft Furniture.

## Dashboard

The Accounting dashboard summarizes sales, purchases, and the bank and cash journals. The Bank card shows a balance of -1,371,452 LE and a Misc. Operations line of 2,000,000 LE; together they equal the 628,548 LE balance of account 101001 Bank in the Trial Balance below.

![Accounting dashboard](screenshots/accounting-01-dashboard.png)

## Configuration

### Chart of Accounts
The chart of accounts lists the account code, name, type, and whether reconciliation is allowed.
![Chart of Accounts](screenshots/accounting-02-chart-of-accounts.png)

### Taxes
Sales and purchase taxes include 14% VAT, zero-rated and exempt taxes, stamp tax, schedule taxes, and withholding taxes.
![Taxes](screenshots/accounting-03-taxes.png)

### Journals
Journals include Sales (INV), Purchases (BILL), bank and cash journals, and miscellaneous journals.
![Journals](screenshots/accounting-04-journals.png)

### Payment Terms
![Payment Terms](screenshots/accounting-05-payment-terms.png)

## Opening Balance

The opening balance is recorded in a miscellaneous journal entry dated October 1: 2,000,000 LE debited to 101001 Bank and credited to 301001 Opening Balance Equity.

![Opening entry](screenshots/accounting-06-opening-entry.png)

## Trial Balance

The Trial Balance for November 2026 shows the initial balance, debit, credit, and end balance of each account. The report is set to posted entries; the banner notes that unposted journal entries also exist in the period.

![Trial Balance](screenshots/accounting-07-trial-balance.png)

## Customer Invoice and Payment

Invoice INV/2026/00006 for Mariam Mahmoud: one 6-Seater Dining Table (12,500 LE untaxed, 1,750 LE VAT, 14,250 LE total). The invoice line is split by analytic distribution between the Cairo and Alex branches, and the invoice is fully paid.

![Paid invoice](screenshots/accounting-08-invoice-paid.png)
![Invoice journal items](screenshots/accounting-09-invoice-journal-items.png)

## Deferred Revenue

Invoice INV/2026/00027 bills the Furniture Installation Package (5,000 LE) with a deferral period from October 27, 2026 to October 27, 2027. Odoo moves the amount from Sales Account to Deferred Revenue and creates monthly deferral entries.

![Deferred invoice](screenshots/accounting-10-deferred-invoice.png)
![Deferral entries](screenshots/accounting-11-deferral-entries.png)

## Vendor Bills

The Bills list shows vendor bills and their payment status.
![Vendor bills](screenshots/accounting-13-vendor-bills-list.png)

Bill BILL/2026/10/0003 from Modern Wood Supplies was created from purchase order P00009 (Purchases button). Untaxed amount 48,300 LE, VAT 14% 6,762 LE, total 55,062 LE.
![Vendor bill](screenshots/accounting-14-vendor-bill.png)

Its journal items debit Raw Materials Inventory per product and VAT Input, and credit Payables.
![Vendor bill journal items](screenshots/accounting-15-vendor-bill-journal-items.png)

## Budgets

Budgets compare the planned amounts with the actual results by analytic account (branch). The list shows three open budgets: Q3 for 2026, Q4 for 2026 - Alex Revenue, and Q4 for 2026 - Alex Expense.

![Budgets list](screenshots/accounting-16-financial-budgets.png)

The Q4 for 2026 - Alex Revenue budget is a revenue budget for Alex Branch, with a period from September 1 to December 31. The budget line shows a budgeted amount of 2,500,000 LE and an achieved amount of 64,450 LE. The Budget Report button opens the comparison report.

![Budget lines](screenshots/accounting-17-budget-lines.png)

The Budget Report compares the budget, committed, and achieved amounts. For Alex Branch it shows a budget of 2,500,000 LE, with 64,450 LE committed and 64,450 LE achieved.

![Budget report](screenshots/accounting-18-budget-report.png)
