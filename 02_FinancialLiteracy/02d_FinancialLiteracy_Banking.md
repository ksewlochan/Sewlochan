---
layout: default
title: Banking
parent: Financial Literacy
nav_order: 4
has_children: false
last_updated_at: Sat 29-Aug-2026 afternoon
---


# The High Five Banking Method
---

- Table of Contents
{:toc}

Last updated: {{ page.last_updated_at }}


# Motivation

Banking will be the core of your financial planning.  Money needs to come in, move around, and end up in storage accounts of various sorts.

Hence you should consider how and where your money is managed.


# Paycheque

Directly off your paycheuque take advantage of your employer’s benefits as much as you can and/or makes sense.
- RRSP Matching
- Pension Funds
- Stock Purchase Plans
- Don't leave money on the table.
- However it is rarely worth it to add in any money above the employer match.  You can almost always get a better account / service outside what your employer offers.

Automatically deposit your net pay into your bank account(s) - see [The High Five Banking Method](#the-high-five-banking-method) below.
- Set up your money transfers to be automatic – the less that you have to worry about it, the better.

Let’s assume you get paid twice a month.
- If you get paid every two weeks then you get two "extra" paycheques above this analysis.
- If you get paid once a month or on some different schedule, adjust as needed.

You will have some "expenses" that can happen:
- Per Paycheque
	- For example, investing, [emergency fund](./02e_FinancialLiteracy_EmergencyFund.md), short term savings, long term savings.
	- This will be automated.
		- Either from your bank account as it allows the automation needed.
		- Sometimes your payroll provider (e.g. ADP) will give you the ability to automate where your money goes.
		- Whatever works best for you.
- Per Month
	- You will need to save half of the monthly expense into the [appropriate bank accounts](#the-high-five-banking-method) per paycheque.
	- Half as we are assuming two paycheques per month.
	- In Month 01 you will be saving the money for Month 02's expenses.
		- Thus when you hit the first of Month 02 you have all the money in your bank account that you need to pay all your expenses for Month 02.
		- The money that you are saving in Month 02 is for the expenses that you will have in Month 03.
		- You are always one month ahead in saving money to pay your bills.
		- Yes, you will have to do a bootstrap of the first month.


# The High Five Banking Method
## Graphically

``` mermaid
	flowchart LR
		IncomeSource["Income Source"] --> ChequingBills["Chequing 01: Bills"]
		IncomeSource --> ChequingLifestyle["Chequing 02: Lifestyle"]
		IncomeSource --> SavingsEmergencyFund["Savings 01: Emergency Fund"]
		IncomeSource --> SavingsShortTerm["Savings 02: Short Term Goals"]
		IncomeSource --> SavingsLongTerm["Savings 03: Long Term Goals"]
		
		ChequingBills --> BankAccountA["Bank Accounts"]
		ChequingLifestyle --> BankAccountB["Bank Accounts"]
		SavingsEmergencyFund --> BankAccountC["Bank Accounts"]
		SavingsEmergencyFund --> TFSAa["TFSA<br>(as cash if room is available)"]
		SavingsShortTerm --> BankAccountD["Bank Accounts"]
		SavingsShortTerm --> TFSAb["TFSA<br>(as cash if room is available)"]
		SavingsLongTerm --> TFSAc["TFSA<br>(as investments)"]
		SavingsLongTerm --> RRSP["RRSP<br>(as investments)"]
		SavingsLongTerm --> LIRA["LIRA<br>(as investments)"]
		SavingsLongTerm --> RESP["RESP<br>(as cash / investments)"]
		SavingsLongTerm --> etc["etc."]
```


## Summary

The concept is to create five bank accounts to help you automatically manage your budget. 

For those accounts that pay bills
- This month you are saving money for next month's bills.  See [Paycheque](#paycheque) above.


|                                           | Type                                  | Purpose                                                                                                                                                                                 |
| :---------------------------------------: | ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span style="font-size: 1.5em;">01</span> | **CHEQUING 01:<br>Bills**             | **Top priority**<br>- Housing<br>- Debt<br>- Utilities                                                                                                                                  |
| <span style="font-size: 1.5em;">02</span> | **CHEQUING 02:<br>Lifestyle**         | **You can lower these expenses to save money**<br>- Personal Care<br>- Hair cuts<br>- Gym<br>- Entertainment<br>- Eating out<br>- Clothes<br>- etc.                                     |
| <span style="font-size: 1.5em;">03</span> | **SAVINGS 01:<br>Emergency Fund**     | **Real Emergencies**<br>- Hospitalization<br>- Job Loss<br>- Home Repairs<br>- Car Issues                                                                                               |
| <span style="font-size: 1.5em;">04</span> | **SAVINGS 02:<br>Short Term Savings** | **Takes less than 12 months to reach**<br>- Upgrades - cell phones, purse, etc.<br>- Special Occasions - Xmas, Birthdays,Anniversaries<br>- Small Travel or Events<br>- Annual Expenses |
| <span style="font-size: 1.5em;">05</span> | **SAVINGS 03:<br>Long Term Savings**  | **Takes more than 12 months to reach**<br>- Down payments<br>- Cars<br>- Homes<br>- Big Travel<br>- Wedding<br>- Baby<br>- etc.                                                         |

## Types of Accounts

Canadians have a large number of account types to choose from:
- Banking ([MoneySense.ca](https://www.moneysense.ca/save/banking/the-best-banks-in-canada/))
	- Chequing
	- Savings
	- Hybris of Chequing and Savings
- TFSA ([Canada.ca](https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/tax-free-savings-account.html))
- RRSP ([Canada.ca](https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/registered-retirement-savings-plan-rrsp.html))
- FHSA ([Canada.ca](https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/first-home-savings-account.html))
- RESP ([Canada.ca](https://www.canada.ca/en/services/benefits/education/education-savings.html))

Some of the above listed "bank" accounts could (and should) be multiple forms.

For example, your **Long Term Savings** could/should be
- A bank account for your next car
- A bank account for your next big travel
- A TFSA for your retirement savings
- An RRSP for your retirement savings
- etc.

On the oppositive side, depending on your individual circumstances, you may not need all of these accounts at a given point in time.

But you should think about these types of accounts and decide how they best fit into your financial journey.


# Joint Accounts

Joint accounts (between spouses, roommates, etc.) can represent an extra level of complication above and beyond The High Five Banking Method.

## Requirements
- There are two people: People 01 and People 02.
- Each person should have their own accounts (banking and investing).
- There should be joint account(s) for shared activities.
- Each person should have their own possessions protected.


## Design

``` mermaid
	flowchart TD
		Paycheque01["Paycheque 01"] --> BankAccount01["Banking Accounts 01"]
		BankAccount01 --> HighFive01["High Five 01"]
		
		Paycheque02["Paycheque 02"] --> BankAccount02["Banking Accounts 02"]
		BankAccount02 --> HighFive02["High Five 02"]
		
		subgraph Joint["Joint"]
			direction TD
			Joint01["Joint 01"]
			Joint02["Joint 02"]
		end
		
		BankAccount01 --> Joint01
		BankAccount02 --> Joint02
		
		Joint --> HighFive["High Five Joint"]
```


Notes
- Each person's paycheque is dropped into their own bank account.
	- This prevents comingling of the funds.
- Each person's Banking Accounts will send money to their own High Five set of accounts.
	- This will allow each person to have their own set of accounts (savings, spending, investing, etc.).
- **Bank Accounts 01** will send funds to **Joint 01**; and **Bank Accounts 02** will send funds to **Joint 02**.
	- The couple needs to decide how much money should be moved to the **Joint 01** and **Joint 02** accounts.  Some options:
		- A percentage - 10% is kept and 90% is moved into the joint accounts.
		- A fixed amount - $100 is kept and the rest is moved into the joint accounts.
	- Each joint account is dually owned by both people so this achieves the legal need for this to be a joint account amoung the partners.
	- But there is a separation so that we know that the funds that end up in **Joint 01** came from **Person 01** and similarly for 02.
	- This achieves tax clarity.
		- If a tax slip is generated for **Joint 01** we know that this should be filed with **Person 01**'s taxes and similarly for 02.
		- A question would be: Is this level of clarity needed?
			- If these accounts will hold very little funds and thus generate very little tax implications then this level of complexity.
- The **Joint** account (i.e. the combination of **Joint 01** and **Joint 02**) will then fund the **High Five Joint** accounts.
	- Thus allowing the couple to fund and live their lives.


# Where to Bank

There are many choices as to where to bank - big 5 as well as smaller providers.

Consider where you will get the best features (e.g. interest rate on Emergency Fund) as opposed to convenience.

Banking should be optimized but not to the expense of peaceful living.

Strike the balance that is good for you.

[https://www.moneysense.ca/save/banking/the-best-banks-in-canada/](https://www.moneysense.ca/save/banking/the-best-banks-in-canada/)


# Appendix

## References

- [https://thepoisedlifestyle.com/the-high-5-banking-method ](https://thepoisedlifestyle.com/the-high-5-banking-method )
- [https://www.youtube.com/watch?v=1_caSO90SKM](https://www.youtube.com/watch?v=1_caSO90SKM)
- [MoneySense.ca: The best banks in Canada](https://www.moneysense.ca/save/banking/the-best-banks-in-canada/)
- [MoneySense.ca: The best chequing accounts in Canada](https://www.moneysense.ca/save/best-chequing-account-canada/)
- [MoneySense.ca: The best high-interest savings accounts in Canada](https://www.moneysense.ca/save/best-high-interest-savings-accounts-canada/)

## Version History

|                                           | Date            | Notes                    |
| :---------------------------------------: | --------------- | ------------------------ |
| <span style="font-size: 1.5em;">01</span> | Wed 12-Aug-2026 | Initial version          |
| <span style="font-size: 1.5em;">02</span> | Fri 21-Aug-2026 | Added **Joint Accounts** |
| <span style="font-size: 1.5em;">03</span> | Sat 29-Aug-2026 | Added **Paycheque**      |
