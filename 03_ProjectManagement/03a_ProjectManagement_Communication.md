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

- Table of Contents
{:toc}

Last updated: {{ page.last_updated_at }}

# How To Communicate

Communication comes down to three things
1. The Message
2. The Words
3. The Artefacts

## The Message


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

See
- [Minto Pyramid Principle](https://untools.co/minto-pyramid/)


Governing Thought (The Main Answer / Recommendation)
- This is the main point that you are trying to communicate.
- The conclusions or recommendations.

Key Argument
- The key arguments or points that support the Governing Thought
- Three is a good number; Four is a good number
- One is not; Eight is not

Data / Fact
- The information that supports the Key Argument


## The Words

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
	- Maybe in context it is relatively easy to understand who "they are".
	- But if instead you said "Bob is happy" then
		- No one has to spend mental energy to map "they" to "Bob".
		- The listener then has more time / energy to focus on the message.


## The Artefacts

Find your lists.

Find your buckets.

Find your tables.

Find your diagrams.

Find your medium:
- The medium of your message can be as important as the message itself.
- If no one can understand your medium, no one is listening to your message.

Search for many sources on how to draft a good diagram, dashboard, power point, etc.


# Key Takeaways

Understand your message.

Use your words carefully.

Craft your medium to communicate your message and to not distract from your message.


# Appendix

## Old Version

[go here](https://sites.google.com/sewlochan.com/sewlochan-com/project-management)

## Version History

|                                           | Date            | Notes                                             |
| :---------------------------------------: | --------------- | ------------------------------------------------- |
| <span style="font-size: 1.5em;">01</span> | Mon 1-Mar-2021  | Initial version                                   |
| <span style="font-size: 1.5em;">02</span> | Mon 10-Aug-2026 | Converted to markdown                             |
| <span style="font-size: 1.5em;">03</span> | Mon 28-Sep-2026 | Added the call out to the Minto Pyramid Principle |
