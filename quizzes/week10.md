# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
a namespace provides scope to a page that you are working on. typically just one per file and one for the entire file.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
a constructor
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
what the function will be returning 
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
THE class Car being instansiated on its own, it can only be implemented by non abstract classes above it
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
virtual means its a default implementation but that it can be over ridden in a  derived class from the base class
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public private internal protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the code within the same class/structure
```