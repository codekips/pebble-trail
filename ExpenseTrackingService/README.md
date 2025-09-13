# Expense Tracking Service

## User Flows
- Add an expense. An expense has the amount spent, what it was spent on, how was it split.
- Remove expenses.
- Show expenses incurred in the past.
- Give a report/ visualization of where most money goes

## Core Entities
- Expense
  - Money moneySpent
  - Payer (Always paid by the logged in user currently, so no need to add)
  - category
  - description
- Money
  - amount
  - currency
- User
  - Name
  - 
- ContactDetails
  - Phone
  - email


## APIs
- POST /v1/