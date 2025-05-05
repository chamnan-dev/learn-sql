+ Introduction to SQL
 SQL is a standard lanuage for accessing and manipulating databases.

1. What is SQL ?
- SQL stands for Structured Query Language
- SQL lets you access and mainpulate database.
- SQL became a standard of the American National Standards Institure (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987.

2 What can SQL do ?
- SQL can execute queries against a database
- SQL can retrieve data from a database
- SQL can insert records in a database
- SQL can update records in a database
- SQL can delete records in a database 
- SQL can create new databases
- SQL can create new tables in database 
- SQL can create stoed procedureds in a database
- SQL can set permissions on tables, procedures, and views
+ SQL is a standard - But ...
Although SQL is and ANSI/ISO standard, there are different versions of the sql language.
However , to be complaint with the ANSI standard , they all support last the major commands (such as SELECT , UPDATE, DELETE, INSERT, WHERE) in a similar manner.

Note: Most of the SQL  database programs also have their own proprietary extensions in addition to the SQL standard!

+ Using SQL IN your web site
To bbuild a web site that shows data from a database , you will need:
- An RDBMS database program (i.e MS Access, SQL Server, MySQL)
- To use a server-side scripting language , like PP or ASP
- To use SQL to get the data you want 
- To use HTML / CSS to style the page

+ RDBMS 

RDBMS stands for Relational Database Managment System.

RDBMS is the basis for SQL , and for all modern database system such as MS SQL Server, IBM DB2, Oracle, MySQL, and Microsoft Access.
The data in RDBMS is stored in database object called tables, A table is a collection of related database entries and it conists of columns and rows.
Look at "Customers" table:
```slq 
 SELECT * FROM Customers.
```

Every table is broken up into smaller entities called fields. The fields in the Customers tables consist of CustomerID, CustomerName, ContactName, Address, City, PostalCode and Country. A field is a column in a table that is designed to maintain specific information about every record in the table.

A record, also called a row, is each individual entry that exists in a table. For example, there are 91 records in the above Customers table. A record is a horizontal entity in a table.

A column is a vertical entity in a table that contains all information associated with a secific field in a table.
