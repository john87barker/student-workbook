# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
To give a common name that connects each document.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
structs are value type while classes are reference type.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
I believe it is Void.
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
string is the type that is being returned.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It prevents the class from being inherited.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It allows a derived class to be able to override it.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, private, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only methods in the same class.
```