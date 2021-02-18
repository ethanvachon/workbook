# Day Four Reflection

**2/18/21**

## In a SQL table, what is the difference between information in a row and information in a column?

A row will represent a single data object, with the first box having the primary key (usually the id). A Column will have a list of all the values of that column prop, including every data object that was posted there.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

the syntax for this is the following:
CREATE TABLE characters (
name VARCHAR(memory allocation) NOT NULL,
age VARCHAR(memory allocation) NOT NULL,
description VARCHAR(memory allocation) NOT NULL,
id int AUTO_INCREMENT NOT NULL,

PRIMARY KEY (id)
);

## What is the difference between the following statements? "Delete from table_name" "Drop table table_name"

Delete from table_name deletes existing records from a table. Drop table table_name deletes the entire table in its entirety.

## Daily Project
