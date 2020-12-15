# Day One Reflection
__12-14-20__

## What problem does using exports solve?
Using exports allows you to separate your javascript code into different files. This de-clutters the javascript document and gives you control over what the files return. This can ensure your users only have access to the code they need without interacting with code they shouldn't.

## How does export differ from export default
Export default only lets you export a single piece of information. Using export, you can export multiple pieces of information that are imported as an object storing all of it.

## What is a benefit of the Module System?
The module system lets your create multiple independent files of javascript code that only export the information that they need to. These modules are reusable and adds a layer of security to the application.