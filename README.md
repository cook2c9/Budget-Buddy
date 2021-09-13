# Budget Buddy

## Introduction

Budget Buddy is an application to help track your finances and shape your budget. The group is composed of the following members:

**Tony Martin** - *Product Owner/Scrum Master/DevOps/GitHub Administrator*

**Tony Herrera** - *Business Logic and Persistence Specialist*

**Connor Cook** - *UI Specialist*

**Yehya Hamed** - *Business Logic and Persistence Specialist / UI Specialist*

## Storyboard (Screen Mockups)

![Images of Storyboard](~link to storyboard image~)

You can access our Storyboard [here](~link to actual storyboard~) at Invision.

## Functional Requirements

1. As a budgeter, I want to have all of my financial information in one place, so that I can make more informed decisions when considering purchases. 
- **Given**: Transaction data is entered, **Given**: Credit card accounts and limits and bank accounts are defined, **When**: The user opens the overview tab, **Then**: The service will display balances across credit cards and bank accounts.

2. As an irresponsible spender at times, I want to be able to understand where my money is going, so that I can make adjustments when making purchases.
- **Given**: Transaction data with spendingType is available, **When**: The user opens the spending breakdown tab, **Then**: The service will present charts/graphs that show how much is spent in each type.

3. As a budgeter, I want to be able to submit transaction data to keep track of it, so that I can have a better visibility of my budget across my accounts and cards.
- **Given**: User has the Date, Dollar Amount, Account used, and the Spending Type known, **When**: User selects enter Transaction, **When**: User submits data in the box, **Then**: The Transaction will be entered into the application database and populate shown in the overview.

## Class Diagram

![Image of Class Diagram](https://i.ibb.co/k5GZCLP/Project-UML.png)

## Class Diagram Description

- customer: 
- updateAccount: 
- paymentInfo: 
- transaction: 
- addBankInfo: 
- addCreditCardInfo: 

## JSON Schema

This is what we plan to export to another application:

>
>{
>    "TransactionID" : "integer",
>    "Date" : "String",
>    "DollarAmount" : "Decimal",
>    "AccountName" : "String",
>    "SpendingType" : "String"
>}
>

## A Product Backlog

Our Product Backlog, or collection of stories can be found [here](https://github.com/marti5a6/Budget-Buddy/projects) in the Projects tab.

## Scrum Board

Our [Scrum Board](https://github.com/marti5a6/Budget-Buddy/projects) can be found in the Projects tab, alongside other stories in the product backlog.

Here is our Scrum Board after the last sprint: ![Image of Scrum Board](~link to image of scrum board~)

## Scrum Roles

**Tony Martin** - *Product Owner, Development Team*

**Tony Herrera** - *Scrum Master, Development Team*

**Connor Cook** - *Development Team*

**Yehya Hamed** - *Development Team*

## Group Meetings/Communication

The group communicates via [Microsoft Teams](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software/). We utiluze a Group Chat for frequent discussion and decision-making, and the voice/video-calling capabilities for our weekly standups.

![Image of Budget Buddy Teams Chat](~link to image of Teams~)
