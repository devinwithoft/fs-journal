# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
abstraction encapsulation inheretence and polymorphism.
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
let property = staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Having data bundled up within its own class instead of jjusting being in the open. IF you want to grab a piece of data you have to first target the class in which the data is contained.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility. Ideally you want a class to just have one responsibility and one reason to change. 
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
class is a data type, or as mick calls it a blueprint, and instance of the class is a creation of an actual thing using that object data  that was previously constructed
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
Proxy objects are a tpye of class that has a bunch of elements within it. IT makes it easy to just target a specific element thats wrapped within the proxy by targetting the proxy itself. How we used appstate.(something) to change the data wrapped within appstate.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
IT cleans up the code overall by allowing for a logical seperation of tasks. Largely functions are grouped by their purpose, and in the case of controller, are further grouped on whether or not we want the client to directly access them
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller sets the logic that involves drawing something to an html page, or handles the incoming data from forms/button clicks/etc as an in intermediary between the form/button accessed by the client in html and the service file which handles the buisiness logic such things 
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
service is pretty broad. Its all sort of logic that isnt simply drawing something to the page or the immediate functions of a button. Whereas controller takes the input of a button being pressed and essentially forwards it to the service, the service runs the buisiness logic that such a click changed. It can access data from the app state or run any other "behind the scenes" function.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
To store the "form" of how you want your data to look. Particularly with objects you intend to make multiple copies of, the model page stores the templates, which the data from app.state is actually used to fill in and controller page is used to render. Model says what something *can* be, but the appstate says what that thing *will* be within whatever constraints the model put on it
```
