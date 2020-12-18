# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```

```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
you would use staff[property], you can use variables to access data if the value of that variable is the same as a key in the object.
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```

```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The S stands for single responsibility, which is one of the most important principals of programming especially in larger scale applications for many reasons. The biggest of which is readability. 
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
You can't access the methods and properties of a class, only an instance of a class. The class before it's been constructed doesn't really exist, It is just waiting to be created.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is used, at least in our templates, to add getter and setter properties to our object containing all the main data used in the project.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
MVC splits up your javascript code into multiple files to increase readability and make your code more clean and organized. It also makes your code more secure, as not all functions and variables are available from anywhere in your project.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is responsible for reformatting data so the service can perform a function that changes the data in the proxy object. The controller also contains all the draw functions, functions that update the page and don't actually change data in the proxy object.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service(s) contain all the essential functions that utilize the getter and setter of the proxy object. The Service is the only part of your javascript that should be changing the data in the State. 
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is the class that you use as the constructor for all your objects that are stored in the AppState.
```

