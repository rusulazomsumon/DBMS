# DBMS
CSC433
 
1.  ## Topics: SQL SELECT ALL Queries.
    

Discussion: Using these queries we can select all data from any given table. The “*” used to represent SELECT ALL properties.

Examples: 1

SELECT * FROM Orders;

Queries Analysis:

Here, SELECT is used for selecting all data from the Orders table of the database:

(*) means Select all fields and

FROM referring to the table name of the database.

After executing the queries we can display all of the data from the Orders table.

![](https://lh3.googleusercontent.com/QkJiBtxLg6p4DioM8iDnnhK0wgg9waM6dJCQegqoaAhAunf8CAaM3f-7i-5TIW_eEVjAAacUpug04qviKXPVO2zXEfI4dPf9g5MAFdhC6-vbFwcryVp1iDjfOLIwpzWhkirBFJlrZmsn0d-rGQ)

  
  
  
  
  
  

2.  ## Topics: SQL SELECT Statement
    

Discussion: We used a SELECT statement to show/ execute data from a table of database.

Examples: 2

SELECT OrderDate FROM Orders;

Queries Analysis:

With these queries we are searching the OrderDate of Orders table. After executing the queries we can see all OrderDate.

  

![](https://lh5.googleusercontent.com/Xoj4odZWy7qUTuqqHv_gFyVb4U6nNkLz8U7X7FZG2FJ7OUr2KAz78KL7H_16F5gPexiQPXeBKA17lUCrBEu2xwpN1LQEN6G_evG3oUlNW2kO8goTQ_IY_wRnLX6-NyqnL9l7FhNpixSMjWOm3Q)

### sub-Topics: SQL SELECT DISTINCT with Count

Description: Using DISTINCT before any fields we can return the number of units of the fields.

Examples: 2.1

SELECT COUNT(DISTINCT CustomerName) FROM Customers;

Queries Analysis:

There is a limitation of SELECT queries alone. In the previous example when we call OrderDate it shows all the dates including duplicate one. If we want to find the number of unique OrderDate then we have to add a special DISTINCT keyword before the searched attribute.

![](https://lh3.googleusercontent.com/cIveF-6MfUmoysmJuw4VjsMYLSNBFo5e5CxyUf1BkDK8qfZOozN-U3HsHWVeSXYBz7isz8dDSqVHA2b0eYX51GegvT1FUGsLWAYvsHFvnMnFSEgi_joICIsZFmCBbm5SkqNEpEf7h7AB0VtVWA)

  

3.  ## Topics: SQL WHERE Clause
    

Description: Using where we can filter or search specific types of value from our database.

Example: 3

SELECT ProductName, Unit, Price From Products WHERE Price BETWEEN 20 AND 40;

Queries Analysis:

In these queries we are showing the Product Name, perses Units, and Price from the Products table, only which product price 20-40 taka.

![](https://lh6.googleusercontent.com/aVuGbASKzFWbFpec7GbSBrBeupJ9uUv2clS7Roig9PuLCnHx9o0-I8-f-bwZFL-_6y2rNCXdLJm-dTAagyZTSAX_QwygRSPODUNsCu6EbEi0CQxS9b5gYjg16LhbgwAuw9AcCLMMFy2LSQlgQw)

  

4.  ## Topics: SQL AND, OR and NOT Operators
    

Description: In the addition of WHERE clause when we need to apply more than one condition then use AND, OR, NOT Operators.

Example: 4

SELECT CustomerID, EmployeeID, ShipperID FROM Orders WHERE (EmployeeID=4 OR EmployeeID=5) AND ShipperID=3;

Queries Analysis:

In this example queries we have used two conditions for selecting data from Orders data table. According the queries if the order process one of employee holding ID 4 or 5 and the shipper ID is 3 only then After executing the queries the system will display Customer ID, and the order process by which employee his/her ID, Shipper ID form the Orders table.

![](https://lh5.googleusercontent.com/pXy1BT5D-fiZniCKrPEgkHd3Riuu9yanowatedcZLJ4ZfC-1IgPJrCoG0ppJS2CokDzn2tixeYaDATrvE5JhiX-15KI2ME1PoFtFfrRvuAEFkXeD60tO-wDgVE7JA4QQPQJg_03orQYOHcfxNw)
