# Understanding Persistent Relational Data

**1.** When using the Vue `cli` what is the command to initialize a project?
<!-- enter you answer in the space below -->
```
vue create (project name) -b or bcw-create if you use the bcw template
```
**2.** Where can you find the scripts to startup you project on localhost?
<!-- enter you answer in the space below -->
```
package.json has a scripts object that contain all available scripts you can run. 
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
this can be done using a v-for loop. this would be used if you needed to render a list of posts on a blog for example.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
a vue component is made of a template, script, and style tag.
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The L stands for the Liskov Substitution Principal. This means that objects of a superclass should be easily replaceable by object of the subclass, meaning that all objects in a subclass should behave the same as an object of the superclass.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
in app.vue, the router-view changes to what the router is pointing at.
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
The state in a component is information only required by a single component. The AppState holds all the information that is needed throughout the entire project.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
The services are responsible for making all calls to a server. 
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
the root can be found in the main.js file.
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
the style tag changes css for a document and using the scoped attribute limits the css to only apply to the one component.
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
This is done with the 'reactive' method.
```