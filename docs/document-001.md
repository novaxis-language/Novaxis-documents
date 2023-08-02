# Introduction

Novaxis is a lightweight and versatile data configuration language designed for easy data manipulation and configuration. It combines the simplicity of TOML, the expressiveness of JSON, and the human-readability of YAML, making it an ideal choice for a wide range of applications.

# Release Date

Novaxis was officially released on 2023. Since then, it has been continuously improved and refined to ensure a smooth and seamless experience for developers and data enthusiasts alike.

# Why Novaxis?

Novaxis was created with simplicity and ease of use in mind. Its straightforward and clean syntax allows users to quickly define and organize data in a natural and intuitive way. Whether you are managing configurations for applications, specifying data structures, or describing complex settings, Novaxis provides an efficient and user-friendly solution.

# Getting Started

Novaxis is designed to be lightweight and easily integrated into your projects. Simply create a .novaxis file and start defining your data in a clear and concise manner.
```PHP
# Define a person object with name and age properties
person
    name ? string
    age ? number

# Configure a list of fruits
fruits ? list = [ "apple", "banana", "orange" ]

# Enable debug mode
debug ? boolean = true

# Interpolation: Reuse the value of age in the greeting message
greeting ? string = "Hello, {person.name}! You are {person.age} years old."
```
> Don't worry if you don't understand something, the next slides contain a complete explanation with examples.

# Key Features

- Simple and Human-Readable: Novaxis offers a minimalistic and readable syntax that makes it easy to understand and work with, even for users new to the language.
- Data Types: Novaxis supports various data types, including strings, numbers, lists, booleans, and even an "auto" type, which automatically detects the data type based on the value.
- Interpolation: Harness the power of interpolation to reference and insert values from other parts of your data structure, creating dynamic and reusable configurations.
- Escape Sequences: Escape sequences allow you to use special characters, such as backslashes, hash symbols, and slashes, with ease and precision.
- Exception Handling: Novaxis provides built-in exception handling for various scenarios, ensuring that errors are properly reported and managed.

# Community and Support

If you have any questions, feedback, or need assistance, feel free to reach out on our official forums or GitHub repository.
