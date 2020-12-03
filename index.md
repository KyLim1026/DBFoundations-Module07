# Title
KLim 
12.02.2020

## Introduction
In this paper, I will explain when to use a SQL UDF, and the differences between Scalar, Inline, and Multi-Statement Functions.

## When you would use a SQL UDF?
When you decide to use parameters to change the results of the query, User Defined Function (UDF) can be useful. You can also test input parameters using IF, IIF or CASE in the functions. 

## Differences between Scalar, Inline, and Multi-Statement Functions
Functions are used to save them in a text file within a database for reuse and use them repeatedly. The differences are below:
#### •	Scalar Function: This function returns a single value as a result of an expression.
#### •	Inline Function: This function returns a table variable as a result of an expression. This function does not require Begin and End in the Create Function statement.
#### •	Multi-Statement Function: This function returns a table variable as a result of an expression like the Inline Function. Multi-Statement Function can create a temporary table and specifying the fields. This is powerful than Inline Function.  

## Summary
In this module, I learned how to use SQL Functions. It looks like there are many Functions that can be useful but more training required. For me, Views are more useful and efficient to use for now. 
