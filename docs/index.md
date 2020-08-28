
Lisa Jones

August 22, 2020

IT FDN 130 A: Foundations of Database Management

Assignment07

https://lisap-01.github.io/DBFoundations-Module07/


# **Functions**

## **Introduction**

* **Built in Functions:**
SQL functions are used to perform calculations on data. There are many types of built-in functions such as the Math/Numeric Functions like SUM, AVG, and COUNT. There are over a hundred built in functions in SQL server!

* **User Defined Function (UDF):**
A user may create custom complex functions that are named and then stored in the Database.
>A function, in any programming environment, lets you encapsulate reusable logic and build software that is “composable”, i.e. built of pieces that can be reused and put together in a number of different ways to meet the needs of the users. Functions hide the steps and the complexity from other code.

(https://www.red-gate.com/simple-talk/sql/t-sql-programming/sql-server-functions-the-basics/), 2020)  (external site)

## **Explain when you would use a SQL User Defined Function (UDF)**

The UDF is a ‘named’ and reusable routine that can perform complex calculations using input parameters.  Wrapping complex code and storing it in a function allows you to call that function whenever needed, without re-writing the code.  This is beneficial for regularly used calculations, and saves time and database resources.

## **Explain the differences between Scalar, Inline, and Multi-Statement Functions**

All 3 of these functions are UDFs. 

* **Scalar functions** are able to contain multiple SELECT statements but can only return a single value.

* **Inline functions** are only able to contain a single SELECT statement and returns results in a table.

* **Multi-Statement functions** are able to contain multiple SELECT statements and returns results in a table.

## **Summary**

SQL functions are simply sub-programs, which are commonly used and re-used throughout SQL database applications for processing or manipulating data.

