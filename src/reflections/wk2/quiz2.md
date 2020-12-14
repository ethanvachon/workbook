# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
To declare a variable, you can use var, let, or const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is defined as a subprogram made to perform a specific task.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
SOLID is an acronym for single responsibility, open-closed, liskov substitution, interface segregation, and dependency inversion. When these principals are applied to a project it is easy to maintain the code and build on top of it. It also allows for easier refactoring and is a part of agile software development.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
The index of pineapple is 2, because it is  third in the list but the index in an array starts at 0.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
You would use you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
A conditional runs specific code based on what condition is being met, for example
if(num%2=0){
  console.log('this number is even')
} else {
  console.log('this number is odd')
}

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```

The missing piece is called the afterthought, it is what changes between every iteration. To increment i, you would use i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM means document object model, the data representation of the web document. The first file accessed is the html, which means it is the first thing to render on the page.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
The 9 types are undefined, boolean, number, string, bigint, symbol, object, function, and finally null.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is the placeholder for information to be passed into a function when it is being written, while an argument is what takes the parameters place when the function is called.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive value is directly stored by the variable, while a reference value isn't directly stored in a variable. The variable contains a address to access the reference value in the heap.
```