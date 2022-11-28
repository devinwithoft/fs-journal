# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronus code happens all at once, where as asynchronous code basically waits for a promise to be fulfilled before executing
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
Essentially, event listeners wait for certain data to be changed and then run specific code once that data has been changed. In a way it is quite similair to async, though listeners could essentially trigger quite frequently as a result of multiple functions whereas async functions are usually self contained.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open/closed principle. It says that code should be open to recieve extensions but closed to recieving modifications, so you can add to something but not completely rewrite it.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback is a function passed into another function as an argument that is invoked by the outerfunction to perform some actions
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is well a promise (in that it could ultimately be broken) for future input. Either that input is returned (promise is kept) or isnt (promise is rejected). Writing a catch() function allows you to capture an error from a promise by logging the error itself. Catch functions only fire if a promise is rejected
 ```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
GET - pulls information from the http
POST - publishes new information to the http
PUT -  updates information within the http
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application programming interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service layer
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
It allows for more organization and allowing for abstracting between the client and the application. Related programs are put into a class together, which must be accessed before any programs contained within can be run. It allows for easy exporting/importing of functions between files too
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
An error on the server's side.
```