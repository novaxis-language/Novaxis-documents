# Classes in Novaxis

## Introduction

In Novaxis, classes play a crucial role in creating custom data structures and organizing code into reusable components. They provide a blueprint for creating objects with their own properties and methods, allowing you to build sophisticated applications with ease.

## Class Declaration

To declare a class in Novaxis, you use the following syntax:
```Javascript
className
    variable ? datatype = value
    anotherVariable ? datatype = value
```

Here's a detailed breakdown of each part of the class declaration:
- **`className`**: This is the name of the class you want to define. It should start with a capital letter and follow the camel case naming convention.

# Example: Creating a Simple Class

Let's create a simple class named **\`Server\`** with two properties, **\`ip\`** and **\`mac\`**:
```PHP
Server
    ip ? String = 0.0.0.0
    mac ? String = 00:00:00:00:00:00
```

# Nested Classes

Novaxis allows you to create nested classes within other classes to build more complex data structures:
```Kotlin
Server
    ip ? String = 0.0.0.0
    mac ? String = 00:00:00:00:00:00

    Server_information
        Storage ? String = 15TB
        Bandwidth ? String = 2TB
```

# Conclusion

Classes are a fundamental feature in Novaxis that enables you to model entities, create reusable components, and build sophisticated data structures. By using classes, you can write more structured and organized code, making your applications easier to understand and maintain. Novaxis offers a flexible and intuitive class declaration syntax that allows you to define classes quickly and efficiently, making it a suitable choice for various development projects.
