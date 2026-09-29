---
layout: default
title: Communication
parent: Project Management
nav_order: 1
has_children: false
last_updated_at: Mon 28-Sep-2026 evening
---

# Communication
---

Everyone Needs to Communicate.
- Provide technical details to your colleagues
- Provide technical details to your manager
- Provide project status to your executive

Different techniques work in different environments.  Consider the following.

- Table of Contents
{:toc}

Last updated: {{ page.last_updated_at }}




# SCQA Framework

**SCQA** stands for **Situation, Complication, Question, Answer**.

While the pyramid structure organizes your arguments logically from top to bottom, **SCQA introduces your topic to the reader**. Instead of dumping your conclusion right away without context—which can shock or confuse an audience—SCQA sets the stage so the conclusion feels natural, urgent, and inevitable.

## The Four Components of SCQA

| Component                                                  | What It Is                                                                                                                                    | Example                                                                                                                            |
| --------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| <span style="font-size: 1.5em;">Situation<br>(S)</span>    | The undeniable, uncontroversial current reality or baseline fact.<br><br>It establishes common ground with your reader.                       | "Our company currently relies on a manual data-entry process for customer onboarding."                                             |
| <span style="font-size: 1.5em;">Complication<br>(C)</span> | The trigger, problem, or changing circumstance that disrupts the situation.<br><br>It creates tension and explains _why_ you need to act now. | "However, customer volume has tripled this quarter, causing massive backlogs, human errors, and a 40% increase in customer churn." |
| <span style="font-size: 1.5em;">Question<br>(Q)</span>     | The natural question raised by the complication.<br><br>It frames the core problem your communication will solve.                             | "How can we scale our onboarding process to handle triple the volume while eliminating errors and reducing churn?"                 |
| <span style="font-size: 1.5em;">Answer<br>(A)</span>       | Your governing thought.<br><br>The core thesis or recommendation of your Minto Pyramid that answers the question.                             | "We must immediately implement an automated, API-driven self-service onboarding portal."                                           |

## The Four Narrative Archetypes (How to order them)

Barbara Minto noted that you don't always have to present SCQA in a strict linear order. Depending on what your audience already knows, you can mix up the sequence to create different psychological effects:

| **Archetype**                                                                       | **Best Used When...**                                                                                                           |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| <span style="font-size: 1.5em;">Standard</span><br><br>S > C > Q > A                | The reader doesn't know the problem well;.<br>You need to walk them through the context step-by-step.                           |
| <span style="font-size: 1.5em;">Stirring</span><br><br>C > S > Q > A                | You need to grab attention immediately with a crisis or shocking change before explaining the baseline.                         |
| <span style="font-size: 1.5em;">Beating Around the Bush</span><br><br>Q > S > C > A | The reader already knows the situation and complication, but you want to remind them of the core question first.                |
| <span style="font-size: 1.5em;">Direct</span><br><br>A > S > C > Q                  | Executives are in a massive rush.<br>You give the answer first, then provide the narrative backstory to prove why you're right. |


# MECE Framework

**MECE** (pronounced _me-see_) stands for **Mutually Exclusive, Collectively Exhaustive**.
- It is the gold-standard framework created by McKinsey & Company (and heavily utilized in the Minto Pyramid Principle) for breaking down a complex problem or topic into clean, logical categories without overlapping or leaving gaps.
- When you build the middle tier of your Minto Pyramid (your key arguments or pillars), those pillars **must** be MECE.

## The Two Rules of MECE

### 01 Mutually Exclusive (No Overlaps):
- **What it means:**
	- Each category is completely distinct from the others.
	- There is no double-counting, repetition, or fuzzy boundaries.
	- If you sort a piece of data, it should fit into _only one_ category.
- _Example violation:_
	- Categorizing expenses into "Marketing," "Advertising," and "Operations" fails because advertising is a subset of marketing.

### Collectively Exhaustive (No Gaps):
- **What it means:**
	- When you put all the categories together, they cover the _entire_ universe of the problem.
	- Nothing important is left out.
- _Example violation:_
	- Categorizing global sales into "North America" and "Europe" fails because it leaves out Asia, South America, and other regions.

## A Quick Example: Evaluating a Business Drop

Imagine you want to figure out why your company's profits dropped this quarter.

### Non-MECE (Messy & Overlapping):
- High employee costs
- Marketing issues
- Spending too much money
- Supply chain problems

_(Why it fails: "Spending too much money" overlaps with employee costs and marketing; it's a messy breakdown.)_

### MECE (Clean & Complete):
- **1. Revenue Decreased** (All factors affecting top-line income)
- **2. Costs Increased** (All factors affecting bottom-line expenses)

_(Why it succeeds: Every financial dollar in a business either falls under revenue or costs—mutually exclusive. Together, they cover 100% of financial performance—collectively exhaustive.)_

## Common MECE Frameworks to Keep in Hand

You don't always have to invent MECE categories from scratch. Consultants often rely on classic mental models that are inherently MECE:
- **The 3Cs:** Customer, Company, Competition (for market analysis)
- **The 4Ps:** Product, Price, Place, Promotion (for marketing strategy)
- **Value Chain:** Inputs $\rightarrow$ Processing $\rightarrow$ Outputs (for operational analysis)
- **Internal vs. External:** (for risk or SWOT analysis)


# The Minto Pyramid Principle

See
- [Minto Pyramid Principle](https://untools.co/minto-pyramid/)


``` mermaid
	flowchart TD
    %% Levels of the Minto Pyramid
    A["Governing Thought<br><i>(The Main Answer / Recommendation)</i>"] 

    %% Key Lines of Argument
    B1["Key Argument 1"]
    B2["Key Argument 2"]
    B3["Key Argument 3"]

    %% Supporting Evidence / Data
    C1["Data /<br> Fact 1.1"]
    C2["Data /<br> Fact 1.2"]
    
    C3["Data /<br> Fact 2.1"]
    C4["Data /<br> Fact 2.2"]
    
    C5["Data /<br> Fact 3.1"]
    C6["Data /<br> Fact 3.2"]

    %% Connections
    A --> B1
    A --> B2
    A --> B3

    B1 --> C1
    B1 --> C2

    B2 --> C3
    B2 --> C4

    B3 --> C5
    B3 --> C6

    %% Styling for visual hierarchy
    classDef topBox fill:#f9f,stroke:#333,stroke-width:2px;
    classDef middleBox fill:#bbf,stroke:#333,stroke-width:2px;
    classDef bottomBox fill:#dfd,stroke:#333,stroke-width:2px;

    class A topBox;
    class B1,B2,B3 middleBox;
    class C1,C2,C3,C4,C5,C6 bottomBox;
```


Governing Thought (The Main Answer / Recommendation)
- This is the main point that you are trying to communicate.
- The conclusions or recommendations.
- The SCQA Framework can be used to develop the Governing Thought.

Key Argument
- The key arguments or points that support the Governing Thought.
- The MECE Framework should be used to create the various Key Arguments.

Data / Fact
- The information that supports the Key Argument.
- - The MECE Framework should be used to create the various Data / Facts.


### AI Prompt

Act as a master executive communications expert trained in the Minto Pyramid Principle and MECE frameworks. 

Please take the text/notes provided below and rewrite them following this exact structure:

1. THE SCQA HOOK:
   - Begin with the Situation (the uncontroversial baseline context).
   - Introduce the Complication (the problem or changing dynamic driving urgency).
   - Pose the Question (the core problem to be solved).
   - Deliver the Answer (your Governing Thought / primary conclusion immediately).

2. THE MINTO PYRAMID (SUPPORTING PILLARS):
   - Break down the core arguments into 2 to 4 Mutually Exclusive, Collectively Exhaustive (MECE) pillars. Ensure there are no overlaps between pillars and that they cover the entire scope of the problem.
   - Under each pillar, organize the supporting evidence, facts, and context cleanly.

3. EDITORIAL REVIEW:
   - Strip away fluff, redundancies, and non-essential filler.
   - At the end, provide a brief bulleted list pointing out any critical data, facts, or logical context missing from my original text that would weaken the argument.

Here is the text to rewrite:
INSERT YOUR TEXT OR NOTES HERE


# The Words

Words matter
- Choose them wisely

Avoid pronouns
- “you”, “me”, “she” will cause people to be defensive
- Focus on the problem / discussion not on the people
- Not “your problem” instead “the problem”

Keep cool
- Communication is only ~9% the words that you use
- The rest is your tone and body language

Active Listening
- Listen to understand
- Do not listen to respond
- Offer your opinion last – first listen to others

Communicate to avoid being misunderstood
- Don’t communicate to be understood
- Communication to not be misunderstood
- An example: you could say "they are happy".
	- Maybe in context it is relatively easy to understand who "they" are.
	- But if instead you said "Bob is happy" then
		- No one has to spend mental energy to map "they" to "Bob".
		- The listener then has more time / energy to focus on the message and is not distracted trying to follow the conversation before you get to the critical part.


# The Artefacts

Find your lists.

Find your buckets.

Find your tables.

Find your diagrams.

Find your medium:
- The medium of your message can be as important as the message itself.
- If no one can understand your medium, no one is listening to your message.

Search for many sources on how to draft a good diagram, dashboard, power point, etc.



# Appendix

## Old Version

[go here](https://sites.google.com/sewlochan.com/sewlochan-com/project-management)

## Version History

|                                           | Date            | Notes                                                            |
| :---------------------------------------: | --------------- | ---------------------------------------------------------------- |
| <span style="font-size: 1.5em;">01</span> | Mon 1-Mar-2021  | Initial version                                                  |
| <span style="font-size: 1.5em;">02</span> | Mon 10-Aug-2026 | Converted to markdown                                            |
| <span style="font-size: 1.5em;">03</span> | Mon 28-Sep-2026 | Added the call out to the SCQA, MECE and Minto Pyramid Principle |
