# Interpolation in Novaxis

## Introduction

Interpolation is a powerful feature in Novaxis that allows you to insert the values of variables into another variables. It enables you to build dynamic strings that include variable values within them. Novaxis provides a simple and flexible way to achieve interpolation.

## Basic Interpolation

To perform basic interpolation, you can use the curly braces **\`{}\`** to enclose the variable name you want to include in the string. The variable name is prefixed with **\`.self\`** to indicate that it's a variable within the same class.

Example:
```PHP
Person
    name ? String = Novaxis
    message ? String = Hello, {.self.name}! // Hello, Novaxis!
```
> In this example, the message variable uses interpolation to include the value of the name variable within the string. When you access the message variable, it will output:

Another example:
```PHP
Person
    name ? String = Novaxis
message ? String = Hello, {Person.name}! // Hello, Novaxis!
```

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
