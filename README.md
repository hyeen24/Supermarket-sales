## Supermarket Sales


## Data

Data Source - https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

- ```Invoice id```: Computer generated sales slip invoice identification number
- ```Branch```: Branch of supercenter (3 branches are available identified by A, B and C).
- ```City```: Location of supercenters
- ```Customer type```: Type of customers, recorded by Members for customers using member card and Normal for without member card.
- ```Gender```: Gender type of customer
- ```Product line```: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel
- ```Unit price```: Price of each product in $
- ```Quantity```: Number of products purchased by customer
- ```Tax```: 5% tax fee for customer buying
- ```Total```: Total price including tax
- ```Date```: Date of purchase (Record available from January 2019 to March 2019)
- ```Time```: Purchase time (10am to 9pm)
- ```Payment```: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)
- ```COGS```: Cost of goods sold
- ```Gross margin percentage```: Gross margin percentage
- ```Gross income```: Gross income
- ```Rating```: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)

## Data Modeling
Using 2 primary key is more realistic as one invoice cannot have only 1 type of item.
![Team document](https://github.com/user-attachments/assets/f5d6c764-aa4c-4331-b7fd-93ab7ea8f21c)

## Creating a PostgresDB
- [ Download Official PostgreSQL ](https://www.postgresql.org/download/)
- [ Creating postgresDB with kaggle data ](https://github.com/hyeen24/Supermarket-sales/blob/main/notebook/postrgresDB.ipynb)

Run SQL shell 
- Login to your sql
```bash
# List your database
\l

# Connect to specific database
\c <databasename>

# Display table
\dt 
```

## THINKING OF WHAT I WANT TO DO NEXT FOR THIS SET OF DATA
