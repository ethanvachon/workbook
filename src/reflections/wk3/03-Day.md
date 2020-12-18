# Day Three Reflection
__12-16-20__

## What are the two common operations that we will set in the handler?
It will almost always include a getter and setter. Getters are how you retrieve values from properties of the class, while Setters are how you edit those values. These are the two essential functions of a class.

## What do you have to make sure you are doing with every Get to ensure the value does not become undefined?
With every get operation, a specified value must be returned with the return keyword. These operations don't just return the value set in them, like in a normal function they rely on the return keyword.


## What are some of the benefits of the proxy object that we are using in our structure for our applications?
Without the proxy object that includes a getter and setter, the values of a class can only be retrieved and edited by directly accessing that class. The problem arises when the class is meant to be private meaning that its properties cannot be accessed in such a direct way.