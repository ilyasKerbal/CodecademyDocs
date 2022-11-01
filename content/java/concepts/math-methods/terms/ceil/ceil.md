---
Title: '.ceil()'
Description: 'Returns the smallest (closest to negative infinity) double value that is a mathematical integer and greater than or equal to the original value.'
Subjects:
- 'Computer Science'
  Tags:
- 'Methods'
- 'Arithmetic'
- 'Double'
  CatalogContent:
- 'learn-java'
- 'paths/computer-science'
---

The **`Math.ceil()`** method returns the smallest (closest to negative infinity) double value that is a mathematical integer and greater than or equal to the original value.

- The result is the same as the argument if the argument value is already equal to a mathematical integer.
- The result is identical to the argument if the argument is NaN, an +/- infinity, or +/- zero.

## Syntax

```pseudo
Math.ceil(x)
```

- `x` is a `double`.
- `ceil` returns a `double`

## Example 1

The following example demonstrates using `.ceil()`:

```java
// Example1.java
public class Example {
  public static void main(String args[]) {
    Double value1 = 8.3;
    Double value2 = 8.9;
    
    System.out.println(Math.ceil(value1));
    System.out.println(Math.ceil(value2));
  }
}
```

This results in the following output:

```shell
9.0
9.0
```

## Example 2

The following example demonstrates using `.ceil()` with negative numbers:

```java
// Example1.java
public class Example {
  public static void main(String args[]) {
    Double value1 = -0.5;
    Double value2 = -1.3;
        
    System.out.println(Math.ceil(value1));
    System.out.println(Math.ceil(value2));
  }
}
```

This results in the following output:

```shell
-0.0
-1.0
```