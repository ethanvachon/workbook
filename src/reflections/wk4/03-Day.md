# Day Three Reflection
__1/6/21__

## What is the purpose of Async / Await?
They are similar to promises, but with a much higher level of abstraction. They are still built upon promises, and essentially have the same purpose and functionality. They wait for the promise to be either resolved or rejected, and either execute the rest of the code or throw up an error message. 

## What must you do in order to await a promise inside a function?
To await a promise with Async / Await, you just have to begin the function with async, and your request should begin with await.
async functionname(){
  let res = await api.get('data')
}

## What are some of the primary benefits of Async / Await?
The main benefit of using Async/Await is that it's much more simple and easy to read. It also allows you to chain multiple async functions easily while keeping some readability intact. It also makes debugging much more easy, using a debugger with normal promises will not step over asynchronous code. With Async/Await, it's just like synchronous code to the compiler.


## Daily Project https://github.com/ethanvachon/day-3-afternoon