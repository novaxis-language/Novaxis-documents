# Interpolation and Mathematical operations in Novaxis

## Introduction

Interpolation is a powerful feature within Novaxis that not only enables you to insert the values of variables into other variables, but also empowers you to solve mathematical operations using interpolations. This dynamic capability allows you to construct dynamic strings that incorporate variable values as well as perform arithmetic calculations. Novaxis provides a straightforward and flexible approach to achieving interpolation, making it a versatile tool for both variable referencing and mathematical computation. This document explores the comprehensive utility of interpolation and mathematical operations in the Novaxis language, offering practical examples and insights to enhance your coding endeavors.

## Basic Interpolation

To implement basic interpolation, employ curly braces **\`{}\`** to encapsulate the variable name you wish to integrate into the string. To denote a variable within the same class, use the **\`.self\`** prefix.

## Mathematical Operations

Novaxis goes beyond simple variable insertion by allowing you to execute mathematical operations within interpolated strings. This empowers you to perform calculations and incorporate the results directly into your string output.

This guide delves into the capabilities of basic interpolation and demonstrates how mathematical operations can be seamlessly integrated into Novaxis, enabling you to create more dynamic and functional code.

## Examples
```PHP
Person
    name ? String = Novaxis
    message ? String = Hello, {.self.name}! // Hello, Novaxis!
```
> In this example, the message variable uses interpolation to include the value of the name variable within the string. When you access the message variable, it will output:
```PHP
Person
    name ? String = Novaxis
message ? String = Hello, {Person.name}! // Hello, Novaxis!
```
```PHP
Person
    age_1 ? Number = 15 + 15
    age_2 ? String = {15 + 15}
```
> When using mathematical operations in the **\`Number\`** datatype, the equation is written normally, so that when using it in any other datatype, the Interpolation property must be used.
>> Note: Mathematical operations can be used by the interpolation property within the **\`Number\`** datatype.
>> <br>Note: A variable that is a number cannot be called because it will be considered a mathematical operation, unless the variable contains an external character such as an underscore.

## Interpolation in Interpolation

Novaxis allows you to nest interpolation within other interpolation statements, enabling you to create more complex dynamic strings. To perform interpolation within interpolation, you can simply enclose the inner interpolation statement within the outer curly braces.

Example:
```PHP
Person
    name ? String = Novaxis

    variableName ? String = name
    variableValue ? String = Hello, {.self.{.self.variableName}}! // Hello, Novaxis!
```
Another example:
```PHP
Person
    name ? String = Novaxis

    variableName ? String = .self.name
    variableValue ? String = {{.self.variableName}} // Hello, Novaxis!
```

## Conclusion

Interpolation in Novaxis provides a convenient way to dynamically include variable values within text, making your data structures more flexible and expressive. By leveraging the power of interpolation, you can create dynamic Novaxis scripts for a wide range of datatypes and values, enhancing the readability and usability of your code. Embrace the versatility of interpolation and leverage its potential to tailor your Novaxis programs to suit your specific needs.

[Next page](document-009.md) | [Previous page](document-007.md)
