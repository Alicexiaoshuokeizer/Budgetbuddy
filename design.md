# Budget Buddy Design 

## Goals
With this application, we would like to have an overview of our monthly spending in different categories, without going across multiple bank accounts and do calculation manually in Excel. Besides, this application also tells me how the money changes over time.

P.S. The money we mean above includes money in different currencies and in different accounts: investment, saving, daily living cost, travel funding.

## Functionalities 
### Version 0.1 (MWE:minimum working example)
  1. A database that can import CSV transactions
  2. UI: Given two dates, print out **all transactions in between**, **total amount spent** and **total amount income** in that period.
  3. UI: Given a date, shows **total balance**.


### Version 0.2
   1. Each transaction can be assigned with **a purpose label** either automatically or manually. The purpose labels belong to a pre-defined basic category set. 
   2. UI: Users can create one or more **event** and assign transactions to a created event.

## Development Details

### Database
- ER Diagram (Entity relation)
- use assertion to check total balance whenever there is a new transaction imported to the database 
