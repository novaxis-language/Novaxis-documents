# Variables in Novaxis

## Introduction
In Novaxis, variables are used to store and manipulate data. They play a crucial role in any programming language, enabling developers to store values and work with them throughout the program's execution.

## Variable Declaration

A variable in Novaxis is declared using the following syntax:
```C#
name ? Datatype = value
```
Let's go through each part of the variable declaration:
- **```name```**: This is the name of the variable. It can start with any character and can contain letters (A-Z or a-z), numbers (0-9), and underscores (_). The name should be chosen carefully to represent the data it holds.
- **```?```**: This is an optional symbol that indicates that the variable has a datatype. If present, the datatype field must follow.
- **```Datatype```**: This field specifies the datatype of the variable, Novaxis supports various datatypes.
- **```=```**: This symbol indicates the assignment of a value to the variable. It is required if the variable has a datatype.
- **```value```**: The value assigned to the variable. The value can be a number, string, list, boolean, or null, depending on the datatype.

## Variable Declaration Methods in Novaxis

In Novaxis, there are two methods to declare variables, both of which are functionally equivalent and offer flexibility in defining variable names and their values.

### Method 1: Using "=" Symbol
The "=" symbol is one of the ways to declare variables and assign values to them. It allows you to implicitly determine the data type of the variable based on the assigned value.

Syntax:
```C#
name ? Datatype = value
```
Example:
```PHP
name ? String = Alice
```

### Method 2: Using ":" Symbol
The ":" symbol is another way to declare variables with assigned values. Like the "=" symbol, it also allows you to define variables and specify their data types.

Syntax:
```C#
name ? Datatype: value
```
Example:
```PHP
name ? String: Alice
```

Both methods offer the same functionality, and you can choose the one that suits your preferences or coding style. Whether you prefer implicit data type inference or explicit data type specification, Novaxis provides you with the flexibility to work with variables in a way that best fits your needs.

## Conclusion

Variables are an essential concept in Novaxis and serve as the building blocks for writing dynamic and flexible programs. By understanding the variable declaration syntax and the different datatypes, you can effectively work with data in your Novaxis code. Remember to adhere to the naming rules for variables to ensure smooth and error-free code execution. Happy coding in Novaxis!
