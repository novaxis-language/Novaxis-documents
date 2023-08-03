# Classes Inheritance

## Introduction

In Novaxis, classes can inherit properties from other classes, creating a hierarchy of data types. The inheritance mechanism allows you to define a new class based on an existing class and reuse its properties while extending or modifying them. Classes in Novaxis are denoted by the **\`Class ? datatype\`** syntax.

## Basic Class Declaration

A basic class declaration in Novaxis consists of the class name followed by a question mark ? and the data type for the class. The properties of the class are defined using the variable = value syntax.

```PHP
Server ? String
    ip = 0.0.0.0
    mac = 00:00:00:00:00:00
```
In this example, we define a class named **\`Server\`** with the data type String. The class has two variables, **\`ip\`** and **\`mac\`**, both of which are of data type String.

## Class Inheritance

To create a class that inherits properties from another class, you can nest the derived class declaration inside the base class. The properties of the derived class will be merged with the properties of the base class. If a property with the same name exists in both classes, the value from the derived class will override the value from the base class.
```PHP
Server ? String
    ip = 0.0.0.0
    mac = 00:00:00:00:00:00
    Server_information
        storage = 15TB
```
In this example, we extend the **\`Server\`** class to include an additional variable **\`storage\`**. The derived class is declared inside the base class, and it inherits the properties **\`ip\`** and **\`mac\`** from the base class **\`Server\`**.

## Class Inheritance with Different Data Types

You can also create a class that inherits from a different data type than the base class. This allows you to change the data type of specific properties in the derived class.
```PHP
Server ? String
    ip = 0.0.0.0
    mac = 00:00:00:00:00:00
    Server_information ? Auto
        storage = 16492674416640
```
In this example, we have a base class **\`Server\`** with properties **\`ip\`** and **\`mac\`**, both of data type **\`String\`**. The derived class is declared with datatype **\`Auto\`**, which means the variable **\`storage\`** in the derived class will have a different datatype than the base class.

## Benefits of Class Inheritance
- **Code Reusability**: Inheritance allows you to reuse properties and behavior from existing classes, reducing code duplication and improving maintainability.
- **Modularity**: Inheritance promotes a modular approach to code organization, making it easier to manage and extend your data types.
- **Customization**: Derived classes can modify or extend the properties of the base class, providing a way to customize data types as needed.
- **Hierarchical Structure**: Inheritance creates a hierarchical structure of classes, making the code more organized and easier to understand.

By utilizing class inheritance in Novaxis, you can create a well-structured and flexible codebase that is easy to maintain and expand as your project evolves.
