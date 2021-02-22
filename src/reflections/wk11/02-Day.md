# Day Two Reflection

**2/23/21**

## What is the difference between a primary key and foreign key?

## What is an Alias?

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
