# lambda Syntax
[ :running: to home][link-home]

<img src="https://img.shields.io/badge/by-Ale.Fuentes.edu-informational?style=for-the-badge&logoColor=white&color=cdcdcd" /> <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />



### Lambda Syntax

```java
    // no arguments
    () -> System.out.println("ale.fuentes.edu")

    // One agurment
    a -> Systme.out.println(a)

    // two arguments
    (x, y) -> x * y

    // with explicit argument types
    (Integer x, Integer y) -> x * y

    // with multiple statements
    (a, b) -> {
        System.out.println(a);
        System.out.println(b);
        return (a + b);
    }
```

<!-- links -->
[link-home]: ../README.md