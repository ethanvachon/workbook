# C# Fundamentals

**1.** What is the purpose of a `namespace`?

<!-- enter you answer in the space below -->

```
The namespace provides structure to the code. It can be used to define a specific part/function to restrict access outside the namespace if the internal access modifier.
```

**2.** What is the difference between a `class` and a `struct`?

<!-- enter you answer in the space below -->

```
The main difference is that a class is a reference type while a struct is a value type.
```

**3.** What is the method that returns an instance of a class, yet it has no return type?

<!-- enter you answer in the space below -->

```
You can use GetReturnType to return an instance of a class without having a return type.
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
it is public, meaning it is available for anything with reference to the Car class.
```

**6.** In the example what is `string` an indication of?

<!-- enter you answer in the space below -->

```
string in this case is indicating what the return type of the start method is
```

**7.** In the example what is `abstract` preventing?

<!-- enter you answer in the space below -->

```
Marking a class as abstract stops it from being used to create an object. new Car() cannot be called.
```

**8.** In the example what is the purpose of `virtual`?

<!-- enter you answer in the space below -->

```
The virtual keyword means that any class derived from the Car class can override this method.
```

**9.** Name four access modifiers:

<!-- enter you answer in the space below -->

```
The four I see most often are public, private, internal, and protected.
```

**10.** If you set a class or method to private, what can access it?

<!-- enter you answer in the space below -->

```
Different than protected, private is the most restrictive access modifier. Private means that only the body of the class has reference to a private method/property.
```
