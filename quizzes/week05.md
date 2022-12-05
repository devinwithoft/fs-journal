# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
create, read, update, delete - basically just ways of interacting with a server via http request
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
.GET grabs information from a link
.POST puts information onto a link
.PUT edits existing information
.DELETE  removes existing information
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object relational mapping. the mapping of persisted data from a data base to objects that we are using in our application. For mongoDB we use mongoose to "communicate" with the data base and "Return" information back to the client
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
put and post
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
asyncronous, synchcronous.
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
Schema, mongoose. mongoose


```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Functions written in between your crud methods to either check for authorization or edit the incoming/outcoming information. It works automatically, unlike the other crud methods. 
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
Request, Response
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
websitehere.com/posts?tag=winter
```