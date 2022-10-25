# C# Fundamentals

**1.** What is the purpose of a `namespace`?

<!-- enter you answer in the space below -->

```
Namespaces are used to organize code into  groups and prevent name collisions that can occur when code base includes multiple libraries. All identifiers at namespace scope are visible to one another without qualification.
```

**2.** What is the difference between a `class` and a `struct`?

<!-- enter you answer in the space below -->

```
Structs are value types whereas Classes are reference types.
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
the data type
```

**7.** In the example what is `abstract` preventing?

<!-- enter you answer in the space below -->

```
It is making the class a base class and abstracting its purpose outward
```

**8.** In the example what is the purpose of `virtual`?

<!-- enter you answer in the space below -->

```
It allows the class to be overridden when referenced in the future.
```

**9.** Name four access modifiers:

<!-- enter you answer in the space below -->

```
Public Private Protected Internal
```

**10.** If you set a class or method to private, what can access it?

<!-- enter you answer in the space below -->

```
Only things within that class
```
