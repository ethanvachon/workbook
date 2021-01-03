# Day Four Reflection
__12-17-20__

## What problems does the Observer pattern seek to solve?
It moves the draw functions to the controller in the form of event listeners. These event listeners are easy to implement because they only require one line of code to be set up and easily trigger draw functions when data in the Proxy State is changed. This means these changes don't have to be stored in the service, so the files are more balanced and organized.

## What are the three mechanisms of the observer pattern?
there is the .on method that sets up the observer pattern from the event emitter in the Utils folder. This method takes in two parameters, which includes what the observer is 'observing' and the function that will run when that data is changed.


## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
The Proxy object stores all the information that is required for the dom. It can't be accessed outside the service, so that provides one of the main advantages of using MVCS. The observer pattern makes it easy to update the dom from updates to data in the Proxy object.