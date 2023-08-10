# Analysis-of-Employees-
Analysis of Employees Using SQL

## Introduction
This task of data analysis was done using SQL. In this analysis, SQL was used to create a database and also solve some basic questions. I used PostgreSQL to carry out data analysis.

## Problem Statement
To solve and provide solutions to the following problems and questions.
1. Select the employee table and show the data where the city is Mumbai and Delhi
2. Select the employee table where the employee first name have both 'a' and 'e' in them.
3. Subset the employee table to have employee with the date of birth above 1990.
4. Subset the salary table to show salaries less than 1 million and sort it in ascending order.


## Skills Demonstrated
1. Creation of Database
2. Creation of Table
3. SELECT * FROM table name
4. Insert Into
5. Values
6. Where clause

## Data Analysis
I had to create a database in pgadmin4. I made use of PostgreSQL for my SQL task.
Firstly, Since we were provided with the data in a CSV file, we had to upload the data into the table created.
- Click on the database created
- Then click on Query tool
- Create a table for employee
- Then type the following code in your query tool

To upload the data into the table for PostgreSQL, 
- Right-click on table
- Select Import/Export Data
- Select import
- choose the location of your csv file on your system
- Click on columns and make sure all columns match the columns on data on csv file
- Then select header is turned on
- Then press ok.

![](pic1.png)

- To upload the salary data into the table, you have to change the column data type from numeric to VARCHAR

![](pic2.png)

- To check if the employee data has been uploaded into the table, SELECT * FROM employee and it returns the table completely full with data.
![](pic3.png)

- Type SELECT * FROM salary to get the table full of data.
![](pic4.png)





- 
