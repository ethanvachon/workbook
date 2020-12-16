# Day Two Reflection
__12-15-20__

## What is the purpose of encapsulation?
Encapsulation is to group together data and the methods that act upon that data in a way where only the methods can change the data. This is because access to that data is not available outside this group unless it is specified to do so. This adds a lot more security and helps you avoid problems arising from shared mutable states.

## What were some of the problems with closures and the underscore prefix?
The underscore prefix is the worst option, as is isn't really true encapsulation. Closures work, but they seem much harder to keep track of and quite a but more messy to look at. Using classes at least in my own opinion is the easiest way to accomplish what you need while keeping your code clean and easy to understand.

## How do we create private variables in a ES6 Class? Why would you do this?
Creating private variables in ES6 is as simple as adding a pound sign directly before a key in a class. This is by far the most simple way to achieve a private variable while still maintaining the same effect a function closure would have. This ensures that this variable can only be changed with methods from the class the variable was declared in.