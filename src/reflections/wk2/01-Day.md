# Day One Reflection
__12-7-20__

## What is Scope?
Scope is where a javascript variable is available in a document. For example, the scope of a var variable may be global, meaning it can be accessed anywhere on the page, or it could also be function scoped. This is when a variable is declared in a function and therefore cannot be accessed outside the "scope" of the function.

## What is Hoisting?
Hoisting is when Javascript takes variable declarations and moves them to the top of their scope. This happens before the code is executed but the variables don't receive their intended value until the declaration is reached. var variables receive a value of undefined, while let and const variables aren't initialized at all ahead of time.

## In what cases might you use let vs const vs var?
Generally, since the release of ES6, using var is for the most part considered bad practice. There may be some extremely rare cases in which using var is useful, but it is almost always better to use let or const. Using const is better suited for a variable you know won't need to be updated or changed, as const variables are constant. Let variables are mainly used, because while they can't be re-declared their values can be updated.