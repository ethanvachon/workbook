# Day Three Reflection

**2/24/21**

## What is SQL injection?

SQL injection is the misuse of a sql query to add onto the end of it some unwanted code. You can put sql code into a parameter it takes into the query to add to it.

## What are 3 methods SQL injection can be done by?

SQL injection can be done by modifying cookies to include SQL queries. You can also do this in the http header. The third type is called a "second order sql injection", which aren't designed to run immediately.

## How can we detect and sanitize SQL injection attacks?

You can use a web application firewall, or an intrusion detection system to automatically detect and prevent these attacks, but those methods shouldn't be your sole protection from these attacks. You should escape all input that are supplied by the user.

## Daily Project
