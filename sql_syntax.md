+ SQL statments
Most of the actions you need to perform on a database are done with SQL statments.
SQL statments consist of keywords that are easy to understand.
The following SQL statment returns all records from a table named "Customers".

Example:

Select all records from the Customers table:
```sql
SELECT * FROM Customers;
```

In this tutorial we will teach you all about the different SQL statments.

+ Database Tables
A database most often contains one or more tables. Each table is identifieed by a name (e.g "Customers" or "Orders"), and contain records (rows) with data.

In this tutorial we will use the well-known Northwind sample database (included in MS Access and MS SQL Server).
Below is a selection from the Customers table used in the example:

+---------------+--------------------+-------------+--------------+---------+-------------+----------+
| CustomerID 	| CustomerName       | ContactName | Address      |  city   |  PostalCode | Country  |
+---------------+--------------------+-------------+--------------+---------+-------------+----------+
|1              | Alfreds Futterkiste| Maria Anders| Obere str. 57| Berlin  | 12209       | Germany  |
+---------------+--------------------+-------------+--------------+---------+-------------+----------+

