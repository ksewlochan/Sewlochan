---
layout: default
title: Earned Value Analysis
parent: Project Management
nav_order: 5
has_children: false
last_updated_at: Mon 10-Aug-2026 noon
---

# Table Complete

Tables are the best thing in the world and using them you can create a very powerful tracking and reporting tool.

- Table of Contents
{:toc}

Last updated: {{ page.last_updated_at }}


# Vision	

You have a project to track to completion.	

It can be broken into two dimensions of the project.
- Can be any dimensions - for example, widgets to make and the steps to make them.
- Each dimension can be broken into the effort for each widget, step, whatever.

You want to track how complete you are.
- How complete is each item in dimension one.
- How complete is each item in dimension two.
- How complete is the project overall.

# Gathering Data

Before we build our table complete we will need to gather some data.

## Dimensions

What are the two dimensions that we want to track?

Some examples are
- Widgets and Steps - let's pick this one for the example
- Web Pages and Documents
- Watches and Steps to Purchase
- etc.

For each dimension you need to determine how many items there are.
- So, for the widgets this may be simple - we are going to build five widgets
- For the steps, it may be more complex.
	- Some widgets have more steps than others.
	- If so, see if you can consolidate and/or generalize the steps.
	- If not, then just do the union of steps - say that four of the widgets have four steps but one has six steps.
- So, lets move forward to build five widgets with each taking six steps (knowing that for four of the five widgets one of the steps is n/a).

## Size

Now we need to decide on the size of each widget and of each step.  Think of size as a percentage as this is easier.  It can work with other units but for now let's assume percentage.

So, let's look at dimension 01 Widgets.

The question to ask yourself is how big is each widget in a percentage basis.

You will have one of the following:
- You Know
	- You know how big each item is compare to the others and can therefore easily assign the percentage size.
- You Know Relatively
	- You can say that the first item is 10 points big.
	- Then assign points to each of the remaining items.
	- Then divide to get percentages.
- You Have to Guess
	- You have no idea so you can guess.
	- This is ok.
- You Cannot Guess
	- It is so complex that you cannot guess.
	- Fine - just make them all the same.

Recap where we are now
- We have the two dimensions.
- We have the number of items in each dimension - five widgets with six steps each.
- We have the size of each item in each dimension.

We can now construct the table (tables rule!!).


# The Table

Construct the following table.  Likely in excel but any way that you want to manage the table is fine.

## Step 01: The Heatmap


|     |             |     | **Widget 01** | **Widget 02** | **Widget 03** | **Widget 04** | **Widget 05** |
| :-: | :---------: | :-: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: |
|     |             |     |      20%      |      20%      |      20%      |      20%      |      20%      |
| 01  | **Step 01** | 10% |               |               |               |               |               |
| 02  | **Step 02** | 20% |               |               |               |               |               |
| 03  | **Step 03** | 15% |               |               |               |               |               |
| 04  | **Step 04** | 30% |               |               |               |               |               |
| 05  | **Step 05** | 10% |               |               |               |               |               |
| 06  | **Step 06** | 25% |               |               |               |               |               |

So, let's look at the above table and appreciate what it shows us
- A column for each widget that we have to build.
- A row for each step that we will have to take to build each widget.
- We know that for four widgets they will not have one of the steps - so we can put in "n/a" into those cells.
- We now have a plan.  See [Status Reports](./03c_ProjectManagement_StatusReports.md) for more details on plans and how to use them.

We can then fill into each cell "DONE" when we have completed that step for that widget.


xxxxxxxxxxxxxxxxxxxxxx



Calculating the size of each item in a dimension.	
	The start planning you need to know the percentage effort of each item in a dimension.
	Assume that dimension one is items.
	How much effort is for each item.
	Option 01: You know, so use these numbers.
	Option 02: You assign the first one 10 points; assign each subsequent a relative number; calculate the percentages.
	Option 03: Just guess.
	Option 04: Make them all the same.
	
Calculating the percentage done in each cell.	
	For each cell at the intersection of dimension one and two you will need to calculate the percentage done of that cell.
	Option 01: You know as there is an independent analysis that tells you the percentage done.
	Option 02: You need to take a guess.
	
	
	
	
	
	
BurnUp	
	You can plan out the percentage done of your project across each time period of work (say, week).
	Then use the Data sheet at the end of each period (e.g. week) to determine the actual percentage done.
