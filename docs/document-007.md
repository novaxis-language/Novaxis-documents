# Classbox in Novaxis

## Introduction

In Novaxis, a "Classbox" is a special construct that allows you to change the inheritance data type for the current class within a specific context. It provides a way to switch or override the data type of the current class temporarily, affecting the properties declared inside the Classbox.

## Basic Classbox Syntax

A Classbox is denoted by the **\`?\`** symbol followed by the desired data type. Inside the Classbox, you can define properties just like in a regular class declaration. The properties declared inside the Classbox will have the data type specified in the Classbox, regardless of the inheritance data type of the surrounding context.
```PHP
Person ? String
    name = John // This variable's datatype is String
    ? Number
    age = 30 // This variable's datatype is Number
    height = 180 // This variable's datatype is Number

```

## Benefits of Classbox
- Selective Data Type Override: Classbox allows you to override the data type of specific properties within a class without affecting the entire class's inheritance data type.
- Contextual Datatype: The properties declared inside the Classbox have a specific contextual data type, which provides flexibility in defining properties for a specific subset of the class.
- Convenient Switching: Classbox simplifies the process of changing the data type for a certain set of properties, making the code more concise and readable.
- Improved Organization: By using Classbox, you can keep related properties together, making the codebase more organized and easier to maintain.
