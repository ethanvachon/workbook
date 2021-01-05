# Day Two Reflection
__1/5/21__

## What are the three states of a promise?
The first state of a promise is 'pending' which is when the promise is still waiting, before it succeeds or fails. The next two are 'Resolved' or 'Rejected'. Resolved is when the promise is completed as expected, and rejected is when the promise fails.

## How do promises seek to resolve the issues of 'callback hell'?
If you have multiple async operations, using callbacks normally causes 'callback hell'. Promises solve this by letting you just attach callbacks rather than passing them. This is called chaining, and it is arguably the best feature of promises.

## What is the difference between .then() and .catch()?
.then() is used for resolved promises. When it is resolved, whatever is next will run. .catch() is the opposite of that. .catch() is run when the promise has some sort of error and is rejected.



## Daily Project https://github.com/ethanvachon/winter2020-mvc-gregslist