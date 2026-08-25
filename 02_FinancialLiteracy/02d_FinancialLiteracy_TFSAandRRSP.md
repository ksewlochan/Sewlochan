---
layout: default
title: TFSA and RRSP Accounts
parent: Financial Literacy
nav_order: 4
has_children: false
last_updated_at: Mon 24-Aug-2026 evening
---


# TFSA and RRSP

It is important to understand some of the basic accounts available to you.

- Table of Contents
{:toc}

Last updated: {{ page.last_updated_at }}


# Summary

|                                 | TFSA                                                                                                                                                                                                                            | RRSP                                                                                                                                                                                                                                              |
| ------------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                        **Link** | [Canada.ca](https://www.canada.ca/en/revenue-agency/services/forms-publications/publications/rc4466/tax-free-savings-account-tfsa-guide-individuals.html)                                                                       | [Canada.ca](https://www.canada.ca/en/revenue-agency/services/forms-publications/publications/t4040/rrsps-other-registered-plans-retirement.html)                                                                                                  |
|      **Taxes on Contributions** | No savings on taxes when money is contributed.                                                                                                                                                                                  | Lowers your net taxable income by your current marginal tax rate.                                                                                                                                                                                 |
|             **Taxes on Growth** | Tax free.                                                                                                                                                                                                                       | Tax free.                                                                                                                                                                                                                                         |
|        **Taxes on Withdrawals** | None                                                                                                                                                                                                                            | Pay tax at your future tax rate the same as “ordinary income”.                                                                                                                                                                                    |
| **Maximum Annual Contribution** | Same maximum for all individuals for each year.<br><br>[Canada.ca](https://www.canada.ca/en/revenue-agency/services/forms-publications/publications/rc4466/tax-free-savings-account-tfsa-guide-individuals.html#contributions)  | 18% of last year's earned income to a maximum.<br><br>[Canada.ca](https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/contributing-a-rrsp-prpp/contributions-affect-your-rrsp-prpp-deduction-limit.html ) |
|                        **Misc** | [Beneficiary vs Success Holder](https://www.planeasy.ca/tfsa-beneficiary-vs-successor-holder-the-difference-is-huge/)<br><br>If you have a spouse ensure that your account is set up as a success holder and not a beneficiary. |                                                                                                                                                                                                                                                   |


# Assumptions

Let's assume the following scenario
- Today
	- Your marginal tax rate is 40%
	- You have $10,000 gross (i.e. before taxes on your paycheque) to invest
- You will invest for your retirement
	- For 20 years
	- At 7% per year rate of return
- 20 Years in the Future
	- Your marginal tax rate will also be 40%
	- Your average tax rate will be 30%
	- Note that we are looking at the two tax rates as
		- If you take out the money with other income then this will be at the marginal rate.
		- If this is the only money you withdraw then it will be at the average tax rate.


# Scenarios

And you have a number of ways that you can invest.

|                                           | Scenario                       | Description                                                                                                                                         |
| :---------------------------------------: | ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span style="font-size: 1.5em;">01</span> | **Just TFSA**                  | - Your paycheque is taxed<br>- You get the net amount in your hands<br>- You invest in a TFSA                                                       |
| <span style="font-size: 1.5em;">02</span> | **RRSP Direct**                | - You invest directly from your paycheque to your RRSP<br>- No taxes are taken                                                                      |
| <span style="font-size: 1.5em;">03</span> | **RRSP Indirect**              | - Your paycheque is taxed<br>- You get the net amount in your hands<br>- You invest in a RRSP<br>- You spend your tax refund on non-investing items |
| <span style="font-size: 1.5em;">04</span> | **RRSP Indirect + Tax Refund** | - Your paycheque is taxed<br>- You get the net amount in your hands<br>- You invest in a RRSP<br>- You invest your tax refund into your RRSP        |
| <span style="font-size: 1.5em;">05</span> | **RRSP Indirect + TFSA**       | - Your paycheque is taxed<br>- You get the net amount in your hands<br>- You invest in a RRSP<br>- You invest your tax refund into your TFSA        |


# Results

Here is how those scenarios pan out.

Recall that these are in common across the scenarios:
- 40% marginal tax rate today
- 7% rate of return
- 20 years investment time frame
- 40% marginal tax rate in 20 years
- 30% average tax rate in 20 years

|                                  | 01: Just TFSA | 02: RRSP Direct | 03: RRSP Indirect | 04: RRSP Indirect + Tax Refund | 05: RRSP Indirect + TFSA      |
| -------------------------------: | ------------- | --------------- | ----------------- | ------------------------------ | ----------------------------- |
|                       Paycheque: | $10,000       | $10,000         | $10,000           | $10,000                        | $10,000                       |
|                           Taxes: | $4,000        | nil             | $4,000            | $4,000                         | $4,000                        |
|                         Net Pay: | $6,000        | nil             | $6,000            | $6,000                         | $6,000                        |
|                      Tax Refund: | nil           | nil             | $2,400            | $2,400                         | $2,400                        |
|               Annual Investment: | $6,000        | $10,000         | $6,000            | $6,000 + $2,400                | $6,000 + $2,400               |
|                    Future Value: | $245,973      | $409,955        | $245,973          | $344,362                       | $245,973 + $98,389 = $344,362 |
| Withdrawal at Marginal Tax Rate: | $245,973      | $245,973        | $147,584          | $206,617                       | $147,584 + $98,389 = $245,973 |
|  Withdrawal at Average Tax Rate: | $245,973      | $286,968        | $172,181          | $241,053                       | $172,181 + $98,389 = $270,570 |

Note that in the **05: RRSP Indirect + TFSA** column for the cells with two numbers, the first number is the RRSP and the second number is the TFSA.

Note that the future value was calculated with the excel FV( 7%, 20 years, pmt, 0 ) formula.

# Analysis

## 01: Just TFSA
- Investing $6,000 for 20 year will give you $245,973 tax free.

## 02: RRSP Direct
- Investing the full $10,000 will result in a larger end value within your RRSP.
- But if you take out the funds at the same marginal tax rate you will end up with the same final net amount ($245,973).
- If you instead you are taking out the amount without other sources of income then your average tax rate will be lower and hence you will withdraw from the RRSP more than the TFSA.

## 03: RRSP Indirect
- If you do not invest the tax refund then your final amount within your RRSP will be the same as your TFSA but but after taxes much less.
- RULE: If you are **not** going to invest the tax refund you are much better off to invest in a TFSA.

## 04: RRSP Indirect + Tax Refund
- By reinvesting the tax refund you will increase your returns over **Scenario 03: RRSP Indirect**.
-  When you reinvest your tax refund into your RRSP your **next year's** refund will be slightly higher than modelled above.
	- This will continue for a number of years as you slowly get the $10,000 back into your RRSP.
	- But by that time a number of years will have passed and you will have lost some compounding.

## 05: RRSP Indirect + TFSA
- By reinvesting the tax refund into your TFSA you will end up with the same amount in your hand after the same marginal tax rate.

## Caveats:
- Depending on how you structure your taxes in 20 years you may actually achieve a little better than the above.

# What We Can Learn From This?

Reinvesting your tax refund is critical to get the same final value.
- If you cannot reinvest your tax refund then put your money into a TFSA.
- In the real world you may not do this as you want that tax refund to be used for something else.  Just be aware of the impact that you are having to your investments by not reinvesting the tax refund.

Money going into an RRSP will always be saving at your marginal tax rate.
- However when it comes out it is unlikely that it is coming out at your marginal tax rate.
- It is much more likely that it will be coming out at your average tax rate as your RRSPs will be one of the main sources of income in retirement.
- Hence it will be taxed lower.
	- Some will have no tax.
	- Some will have the first level of taxes.
	- Some the second.
	- Until you reach the same marginal tax rate that it went in at.
	- And if you are lucky and you are making more in retirement than you were when working; don't worry about it.  This is a good problem to have.


# Heuristics

So given all of the above analysis there is still an additional complication: your income is not static through out your career.  So how do you decide on which to invest in first?

> Caveat: It is best to max out both.  This is your best option.  But if you cannot then what do you do?

|                                   | Description                                                                                                                                                                                                                                                                                                                                                 | Conclusion                                                                                                                                         |
| --------------------------------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
|   **Same Tax Rate in Retirement** | Your marginal tax rate today is the same as your marginal tax rate in the future.<br><br>Then it does not matter if you maximize TFSA first or RRSP first.<br><br>Your after tax (none for TFSA and marginal for RRSP) gives you the same future income to spend.                                                                                           | Does not matter TFSA or RRSP.<br><br>But if close choose RRSP as you will likely be withdrawing at the average tax rate not the marginal tax rate. |
|  **Lower Tax Rate In Retirement** | Your marginal tax rate today is the lower than your marginal tax rate in the future.<br><br>So you are a student or a new employee.<br><br>You are not earning much money.<br><br>You expect that you will be earning more money in retirement than you are today.<br><br>So you would save a small amount of taxes today and pay more taxes in the future. | Maximize TFSA first.                                                                                                                               |
| **Higher Tax Rate In Retirement** | Your marginal tax rate today is the higher than your marginal tax rate in the future.<br><br>You are at a high-ish point in your earning.<br><br>You expect that you will be earning less money in retirement than you are today.<br><br>So you would save a large amount of taxes today and pay less taxes in the future.                                  | Maximize RRSP first.                                                                                                                               |

With all the above analysis the general conclusion is:
- If you are **earning more today** than you expect to earn in retirement, then maximize **RRSP** first.
- If you are **earning less today** than you expect to earn in retirement, then maximize **TFSA** first.

Stated another way:
- If your marginal tax rate today is more today than you expected marginal tax rate in retirement to be, then maximize RRSP first.
- If your marginal tax rate today is less today than you expected marginal tax rate in retirement to be, then maximize TFSA first.

If the above is too complex and confusing and you want something simple, here it is
- YES, I can maximize both my TFSA and my RRSP
	- Just do it (maximize both) and don't worry any more
- NO, I cannot maximize both today
	- Are you making the same or more today than you expect to make in retirement
		- Maximize your RRSP first
	- Else
		- Maximize your TFSA first


# Appendix

## Attachments

| Attachment                                                                              | Description                                   |
| --------------------------------------------------------------------------------------- | --------------------------------------------- |
| [Sample Excel File](../assets/images/02d_FinancialLiteracy_TFSAandRRSP_TFSAvsRRSP.xlsx) | Excel file with the results table from above. |


## Version History

|                                           | Date            | Notes                                       |
| :---------------------------------------: | --------------- | ------------------------------------------- |
| <span style="font-size: 1.5em;">01</span> | Mon 24-Aug-2022 | Initial version                             |
