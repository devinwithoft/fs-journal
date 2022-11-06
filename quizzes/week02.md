# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let const var
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
Code designed to perform a specific task such as calculating a value or altering data
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
set of five principles of object orientated class design.

```

**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
[2] because indexes technically start at zero
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
let conditional = true
if (condition == true){
    return "this is an example of a conditional)
} else {
    return "this is still an example of a conditional, but this would part would only trigger if the conditional wasnt true"
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
its called the after thought, its the last part of the loop, and essentially sets the speed of the for loop. To increase by one after each loop has completed, you'd type i++
```

**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model, HTML is accessed first
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
boolean, null, undefined, number, string, object, array, function, symbol
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
The parameters are the variables defined when you first create a function, and arguments are the values that are declared when you actually invoke the function

You write the function with the parameter inside, but once evoked you can run through arguments in place of that parameter to do different stuff
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values store the actual values that they are. They can be altered, but not changed in the same way that reference values can be. A string value can be changed from one word to the next, but string itself cant directly be set to the value of something tethered to an if statement. Reference values dont store the actual primitive values in themselves, but rather store references to them in various ways. (For reference values) an array for example is the reference of the primitive string/number/etc values inside of it. An object makes references to the primitive values inside of it, but it itself isnt one. A function stores references to variables that it manipulates.
```