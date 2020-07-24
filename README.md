# Query a Digital Music Store
This lab related to **Data Analysis Track 1 Million Arab Coders Initiative** from Udacity.
## Name of Database
Chinook-Database
## Intersting question about yhe database
### Q1.
The Chinook database contains all invoices from the beginning of 2009 till 
the end of 2013. The employees at Chinook store are interested in seeing 
all invoices that happened in 2013 only. Using the Invoice table, write a 
query that returns all the info of the invoices in 2013.
### Q2.
The Chinook team decided to run a marketing campaign in Brazil, 
Canada, india, and Sweden. Using the customer table, write a query 
that returns the first name, last name, and country for all customers 
from the 4 countries.
### Q3.
Using the Track and Album tables, write a query that returns all the songs that
start with the letter 'A' and the composer field is not empty. Your query 
should return the name of the song, the name of the composer, and the title of
the album.
### Q4.
The Chinook team would like to throw a promotional Music Festival for their top
10 cutomers who have spent the most in a single invoice. 
Write a query that returns the first name, last name, and invoice total for 
the top 10 invoices ordered by invoice total descending.
### Q5.
Use the Invoice table to determine the countries that have the most invoices. 
Provide a table of BillingCountry and Invoices ordered by the number of invoices 
for each country. The country with the most invoices should appear first.
### Q6.
We would like to throw a promotional Music Festival in the city we made the most money.
Write a query that returns the 1 city that has the highest sum of invoice totals. 
Return both the city name and the sum of all invoice totals.
check your solution
The top city for Invoice dollars was Prague with an amount of 90.24
### Q7.
The customer who has spent the most money will be declared the best customer. 
Build a query that returns the person who has spent the most money. 
I found the solution by linking the following three: 
Invoice, InvoiceLine, and Customer tables to retrieve this information, 
but you can probably do it with fewer!
check your solution
The customer who spent the most according to invoices was Customer 6 with 49.62 in purchases.
### Q8.
The team at Chinook would like to identify all the customers who listen to Rock music. 
Write a query to return the email, first name, last name, and Genre of all Rock Music listeners. 
Return your list ordered alphabetically by email address starting with 'A'.
Check your solution
Your final table should have 59 rows and 4 columns.
### Q9.
Write a query that determines the customer that has spent the most on music for each country. 
Write a query that returns the country along with the top customer and how much they spent. 
For countries where the top amount spent is shared, provide all customers who spent this amount.
You should only need to use the Customer and Invoice tables.
Check Your Solution
Though there are only 24 countries, your query should return 25 rows because the United Kingdom 
has 2 customers that share the maximum.
## This is the ERD of the system
![1MAC](https://user-images.githubusercontent.com/56017399/70856482-ff26bd00-1eee-11ea-8e71-69c9ad7e7ccf.png)
