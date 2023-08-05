# Escape Sequences in Novaxis

## Introduction
In Novaxis, escape sequences are special character combinations that allow you to include characters with special meanings or insert characters that cannot be directly typed or printed as they are. These sequences start with a backslash (**\`\\`**) followed by one or more characters. They are used to represent specific characters or symbols within strings or variable values.

## Escape Sequences in Novaxis:
- **`\\`**: Represents a literal backslash character.
- **`\#`**: Represents a hash (#) symbol.
- **`\/`**: Represents a forward slash (/) symbol.
- **`\S`**: Represents a space character, the most important use is the beginning and end of the value of string variables.

## Usage Example:
```PHP
message ? String = Welcome to Novaxis: \S Your pathway to new possibilities! // Output: Welcome to Novaxis:  Your pathway to new possibilities!
```
```PHP
message ? String = \SWelcome to Novaxis\S
```
> They are usually used at the beginning and end of string variables because they contain a regular space that the Interpreter does not read

Escape sequences in Novaxis are useful when you need to include characters that have special meanings, like backslashes or reserved symbols, within strings. They also enable you to include characters that are not directly accessible through standard keyboard input.

By using escape sequences, you can enhance the flexibility and expressiveness of your Novaxis code, making it easier to handle complex data and improve the readability of your scripts.

Remember that any escape sequence in Novaxis must begin with a backslash (\), and the combination of the backslash and the subsequent characters will define the representation of the escape sequence. Utilize escape sequences whenever necessary to handle special characters effectively in your Novaxis scripts.

[Previous page](document-008.md) | [First page](document-001.md)
