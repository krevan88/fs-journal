# C# Fundamentals

**1.** What is the purpose of a `namespace`?

<!-- enter you answer in the space below -->

```
Namespaces are used to provide a "named space" in which your application resides. They're used especially to provide the C# compiler a context for all the named information in your program, such as variable names.
```

**2.** What is the difference between a `class` and a `struct`?

<!-- enter you answer in the space below -->

```
Struct are value types whereas Classes are reference types.
```

**3.** What is the method that returns an instance of a class, yet it has no return type?

<!-- enter you answer in the space below -->

```
The constructor is a special method that is used to construct an instance of a class.
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
Public
```

**6.** In the example what is `string` an indication of?

<!-- enter you answer in the space below -->

```
the data type
```

**7.** In the example what is `abstract` preventing?

<!-- enter you answer in the space below -->

```
Defines that the class is to be a base of other classes.
```

**8.** In the example what is the purpose of `virtual`?

<!-- enter you answer in the space below -->

```
Allows it to be called to another class.
```

**9.** Name four access modifiers:

<!-- enter you answer in the space below -->

```
Public, private, protected, internal
```

**10.** If you set a class or method to private, what can access it?

<!-- enter you answer in the space below -->

```
Only can be accessed within the same class or strut.
```
