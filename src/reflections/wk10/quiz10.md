# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Define the space where your code resides (AppName.Location)
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
classes are ref types and structs are value types
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
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
data type of the return
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
keeps it from being instantiated
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
to allow the method to be overridden
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected and internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
the code is only accessable within the same class
```