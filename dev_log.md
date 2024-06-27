# Budgetbuddy Development Log

## June 24, 2024
1. created tables in Budget.db according to ER Diagram
2. started writing pipeline to convert revolut data into database data in revolut2transa.ipynb

#### NEXT STEP
change 'amount' to 'spent' and 'income' based on positive and negative number in exported csv and write it to database csv

## June 25, 2024
1. change 'amount' to 'spent' and 'income' based on positive and negative number
2. change primary key of Transactions to AUTOINCREMENT 
3. tried to insert data to the database table but integrityerror occured

#### NEXT STEP
fix the integrity error and import the dataframe to Transactions table 

## June 26, 2024
1. inserted the data into the database successfully by fixing the NaN value in date value
2. add Accounts table setting to ER Diagram and created the table in the database

#### NEXT STEP
verify whether a row already exists in the database
RBS data pipeline

#### IDEAS 
Generalize pipeline into scripts
push project into Github