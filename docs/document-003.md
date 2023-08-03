# Datatypes in Novaxis

## Introduction

In Novaxis, data types define the nature of the values stored in variables. Novaxis supports various data types, allowing you to represent different kinds of information in your data structure. Understanding these data types is essential for effectively working with Novaxis and ensuring your data is correctly structured.

## Datatypes

1. **String**:
Strings in Novaxis are sequences of characters, such as letters, numbers, and symbols. They are used to represent textual data. In Novaxis, strings are declared without enclosing them in quotes, making it easy to work with text directly. For example:
	```PHP
	name ? String = John Doe
	message ? String = Hello, Novaxis!
	```

2. **Number**:
Numbers in Novaxis represent numeric values, including integers and floating-point numbers. Novaxis supports both positive and negative numbers. Numeric values can be directly assigned to variables without any additional syntax. For example:
	```PHP
	age ? Number = 30
  	pi ? Number = 3.14159
  	```
3. **Boolean**:
Booleans are data types with only two possible values: true or false. They are used to represent binary conditions, such as yes/no or on/off states. Booleans are straightforward to use in Novaxis:
	```PHP
 	is_student ? Boolean = true
	is_working ? Boolean = false
 	```
4. **List**:
Lists in Novaxis are ordered collections of values. They can contain elements of different datatypes and allow you to group related data together. Lists are declared using square brackets and separating elements with commas. For example:
	```Python
	numbers ? List = [1, 2, 3, 4, 5]
	fruits ? List = ['apple', 'banana', 'orange']
 	```
 5. **Null** or **None**:
The null or none datatype in Novaxis represents the absence of a value. It is often used to indicate that a variable does not have any meaningful data. To declare a variable with null value, simply use the **\`none\`** keyword (or **\`null\`**):
	```Javascript
 	empty_value ? None = NONE
 	empty_value ? None = NULL
	empty_value ? Null = NONE
	empty_value ? Null = NULL
 	```
	> It does not matter whether the result is all uppercase or lowercase letters, or some are uppercase letters:
	```PHP
	empty_value ? Null = null
 	```

# Conclusion

Understanding the different datatypes available in Novaxis is essential for effectively working with data in your programs. Whether you are dealing with text, numbers, boolean values, or lists, Novaxis provides a simple and intuitive syntax to handle various types of data. By leveraging these datatypes, you can create powerful and flexible applications in Novaxis.
