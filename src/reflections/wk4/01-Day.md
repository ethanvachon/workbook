# Day One Reflection
__1/4/21__

## What are some of the signs and causes of Callback Hell?
A big sign of code being 'callback hell' is if a function becomes a giant pyramid of conditionals. A big cause of this is having your code all run from top to bottom.

## What does the asynchronous mean and how are callbacks involved?
asynchronous means that something will take some time and will eventually run in the future. Callbacks are the function that runs after the request is finished.

## Summarize the 3 ways to avoid / fix Callback Hell
First it is important to keep your code shallow, meaning that you should take opportunities to make your functions shorter and more modular. This also relates to number two, which is to modularize your code. This is similar to the concept of single responsibility for functions. Lastly, it is important to handle every single error. Plan on all your requests having an error and deal with that accordingly.


## Daily Project https://github.com/ethanvachon/day-1-afternoon