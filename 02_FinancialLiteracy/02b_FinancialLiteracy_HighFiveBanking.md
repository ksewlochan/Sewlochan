---
layout: default
title: The High Five Banking Method
parent: Financial Literacy
nav_order: 2
has_children: false
last_updated_at: Fri 21-Aug-2026 evening
---


# The High Five Banking Method

A good methodology to think about how to structure your bank accounts.

- Table of Contents
{:toc}

Last updated: {{ page.last_updated_at }}


# References / Credit

- [https://thepoisedlifestyle.com/the-high-5-banking-method ](https://thepoisedlifestyle.com/the-high-5-banking-method )
- [https://www.youtube.com/watch?v=1_caSO90SKM](https://www.youtube.com/watch?v=1_caSO90SKM)

# Graphically

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


# Summary

The concept is to create five bank accounts to help you automatically manage your budget. 

For those accounts that pay bills
- This month you are saving money for next month's bills.
- So by the start of next month your bank account has all the money needed to pay next month's bills.
- Yes, you will have to do a bootstrap of the first month.


|                                           | Type                   | Purpose                                                                                                                                                                                 |
| :---------------------------------------: | ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span style="font-size: 1.5em;">01</span> | **Bills**              | **Top priority**<br>- Housing<br>- Debt<br>- Utilities                                                                                                                                  |
| <span style="font-size: 1.5em;">02</span> | **Lifestyle**          | **You can lower these expenses to save money**<br>- Personal Care<br>- Hair cuts<br>- Gym<br>- Entertainment<br>- Eating out<br>- Clothes<br>- etc.                                     |
| <span style="font-size: 1.5em;">03</span> | **Emergency Fund**     | **Real Emergencies**<br>- Hospitalization<br>- Job Loss<br>- Home Repairs<br>- Car Issues                                                                                               |
| <span style="font-size: 1.5em;">04</span> | **Short Term Savings** | **Takes less than 12 months to reach**<br>- Upgrades - cell phones, purse, etc.<br>- Special Occasions - Xmas, Birthdays,Anniversaries<br>- Small Travel or Events<br>- Annual Expenses |
| <span style="font-size: 1.5em;">05</span> | **Long Term Savings**  | **Takes more than 12 months to reach**<br>- Down payments<br>- Cars<br>- Homes<br>- Big Travel<br>- Wedding<br>- Baby<br>- etc.                                                         |

# Types of Accounts

Canadians have a large number of account types to choose from:
- [Banking](https://www.moneysense.ca/save/banking/the-best-banks-in-canada/)
	- Chequing
	- Savings
	- Hybris of Chequing and Savings
- [TFSA](https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/tax-free-savings-account.html)
- [RRSP](https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/registered-retirement-savings-plan-rrsp.html)
- [FHSA](https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/first-home-savings-account.html)
- [RESP](https://www.canada.ca/en/services/benefits/education/education-savings.html)

Some of the above listed "bank" accounts could (and should) be multiple forms.

For example, your **Long Term Savings** could/should be
- A bank account for your next car
- A bank account for your next big travel
- A TFSA for your retirement savings
- An RRSP for your retirement savings
- etc.

On the oppositive side, depending on your individual circumstances, you may not need all of these accounts at a given point in time.

But you should think about these types of accounts and decide how they best fit into your financial journey.

# Where to Bank

There are many choices as to where to bank - big 5 as well as smaller providers.

Consider where you will get the best features (e.g. interest rate on Emergency Fund) as opposed to convienence.

Banking should be optimized but not to the expense of peaceful living.

Strike the balance that is good for you.

[https://www.moneysense.ca/save/banking/the-best-banks-in-canada/](https://www.moneysense.ca/save/banking/the-best-banks-in-canada/)


# Joint Accounts

Joint accounts (between spouses, roommates, etc.) can represent an extra level of complication above and beyond The High Five Banking Method.

## Requirements
- There are two people: People 01 and People 02.
- Each person should have their own accounts (banking and investing).
- There should be joint account(s) for shared activities.
- Each person should have their own possessions protected.


## Design

``` mermaid
	flowchart LR
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
- Bank Accounts 01 will send funds to Joint 01; and Bank Accounts 02 will send funds to Joint 02.
	- Each joint account is dually owned by both people so this achieves the legal need for this to be a joint account amoung the partners.
	- But there is a separation so that we know that the funds that end up in Joint 01 came from Person 01 and similarly for 02.
	- This achieves tax clarity.
		- If a tax slip is generated for Joint 01 we know that this should be filed with Person 01's taxes and similarly for 02.
		- A question would be: Is this level of clarity needed?
			- If these accounts will hold very little funds and thus generate very little tax implications then this level of complexity.



# Appendix

## Version History

|                                           | Date            | Notes                    |
| :---------------------------------------: | --------------- | ------------------------ |
| <span style="font-size: 1.5em;">01</span> | Wed 12-Aug-2026 | Initial version          |
| <span style="font-size: 1.5em;">02</span> | Fri 21-Aug-2026 | Added **Joint Accounts** |
