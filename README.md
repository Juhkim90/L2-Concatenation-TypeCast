## Concatenation 

Adding strings together, appending (add to the end)

"Hello" + "World" --> "HelloWorld" 

## Type Cast 

To force a data type

Why would this be useful??

What is 5 + 4? = 9 
What is "5" + "4" = 54

When we get inputs that are numbers, they are initally __string__ types so we must cast the __int__ type in order to do numerical operations. 

Similarly, when we use `print()` everything must be of the same time.

`age = 21`
We cannot `print("My age is " + 21)`

This will give us an error because we cannot __add__ or __concatenate__ two different data types. 

### To an integer type

`int(variableName)`

### To a string type
`str(variableName)`

### To a float type
`float(variableName)`

### To a bool type
`float(variableName)`

## Char

[ASCII Values](https://durofy.com/ascii-values-table-generator-in-c)

Each character is associated with an ASCII value. We are concerned with the decimal system. 

A = 65 
a = 97

This is how the computer alphabetizes strings. 

### Character with ACSII value
The `chr()` function returns a string representing a character whose Unicode code point is an integer.

`chr(65)` --> returns A

### ASCII Value of Character
The `ord()` function returns an integer representing the Unicode character.

`ord("1")` --> returns 49
