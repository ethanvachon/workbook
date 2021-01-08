# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
normal code is synchronous, meaning it executes code line by line and will not execute the next line until the current line is finished. Asynchronous code doesn't do this, code can keep executing before a line is finished. This is good for functions that might take a while, like if you're contacting a server.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener waits for specific data to change, and when it does, it will execute a function that it was given.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The O stands for Open / Closed. This means a class should be able to be extended, but not open to modification.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
This is a function that is passed into another function as an argument. 
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise says that there will be something coming in from a server. An error is captured from a promise using .catch(), which will be executed if there is a problem getting the data requested. 
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```

```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
API stands for application programming interface.
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
Calls to an API should be in the Service folder, while the try/catch should be in the controller.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation is one of the fundamental parts of object-oriented programming. It ensures that data can't be accessed where it isn't meant to be, which improves security and stability of code.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
Successful requests will have a response code in the 200s
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
A response code of 500-599 represents a server error.
```