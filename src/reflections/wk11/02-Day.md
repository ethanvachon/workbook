# Day Two Reflection

**2/23/21**

## What is the difference between a primary key and foreign key?

A primary key is the first column in a table, that you would normally use to find a specific row. A foreign key is the Id of a row of another table. This is used for setting up data relationships in SQL.

## What is an Alias?

An alias is just a placeholder name for a table, like creating a variable. It acts as a key to the value of a table.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections?

CREATE TABLE doctors (
id INT NOT NULL AUTO_INCREMENT,
-- CODE OMITTED
PRIMARY KEY (id)
)

CREATE TABLE patients (
id INT NOT NULL AUTO_INCREMENT,
-- CODE OMITTED
PRIMARY KEY (id)
)

CREATE TABLE doctors (
id INT NOT NULL AUTO_INCREMENT,
doctorId INT NOT NULL,
patientId INT NOT NULL,

FOREIGN KEY (doctorId)
REFERENCES doctors(id),
FOREIGN KEY (patientId)
REFERENCES patients(id),
)

## Daily Project
