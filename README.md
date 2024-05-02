# PYTHON
-WEEK1
DAY1

What is PYTHON- It is a popular programming language that is created by GUID VAN ROSSUM and released in 1991.
-IT is used for 
1. WEB DEVELOPMENT (server side)
2. SOFTWARE DEVELOPMENT
3. MATHEMATICS
4. STYSTEM SCRIPTING

   WHAT CAN PYTHON DO
   -Has a simple syntanx similar to the English language
   -Python has syntax that allows developers to write programs with fewer lines some other programming languages.

   PYTHON IDENTATION
   - Refers to the spaces at the beginning of a code line. Python uses identation to indicate a block of code.
   - We have python programs which can be done using any text editor, Visual studio code, Sublime, Pycharm, and Notepad++ (window users) are some recommended options.
  
   - VARIABLES AND TYPES
     

1. **Variable:** The basic unit of a program that stores data. It's assigned a value using the equal sign (=).

2. **Assignment Operator:** The equal sign (=) is used to assign values to variables.

3. **Jupyter Notebooks:** Cells in Jupyter Notebooks can be executed using Shift + Enter. A new cell can be inserted by clicking outside the margin and typing 'a'.

4. **Variable Naming Rules:**
   - Cannot begin with a number.
   - Can include upper and lower case letters, as well as underscores.
   - Variable names traditionally begin with lowercase letters in Python.

These principles are fundamental in programming and are essential for writing clear, understandable, and maintainable code in Python.

iINTRODUCTION TO VARIABLES

- **Types of Variables in Python:**
  - Integers: Whole numbers.
  - Floats: Decimal numbers.
  - Complex Numbers: Used for complex mathematical calculations.
  - Strings: Collections of characters.
  - Booleans: True or false values.

- **String Concatenation:** The plus sign (+) is used to concatenate strings in Python. However, it cannot be used to add strings and numbers together.

- **Error Messages:** Error messages in Python provide useful information for debugging. They indicate issues in the code and help identify where problems occur.

Understanding these concepts is essential for effectively working with variables and data types in Python programming.


DATA STRUCTURES.


- **Data Structures in Python:** Data structures allow for the storage of a collection of values in a single variable.

- **List:** A fundamental data structure in Python that can contain any data type, including other lists. Lists are ordered and mutable, meaning you can change their elements. The length of a list can be determined using the `len()` function.

- **Set:** Another data structure in Python, similar to a list, but it only contains unique elements. Sets are declared using curly braces `{}`. Sets are unordered and mutable, and they automatically remove duplicate elements.

Understanding lists and sets is crucial for managing collections of data efficiently in Python programs.

INTRODUCTION TO DATA STRUCTURES.

- **Sets:** Sets in Python are unordered collections of unique elements. Unlike lists, the order of elements in a set is not important. Sets are declared using curly braces `{}`.

- **Tuples:** Tuples are similar to lists but immutable, meaning they cannot be modified once declared. They are useful for storing data that should not be changed, such as X-Y coordinate pairs or configurations. Tuples are declared using parentheses `()`.

- **Dictionaries:** Dictionaries are collections of key-value pairs, where each key is associated with a value. They are similar to a word and its definition in a book's glossary. Dictionaries are declared using curly braces `{}` with key-value pairs separated by colons `:`.

Understanding the characteristics and usage of sets, tuples, and dictionaries is essential for efficient data manipulation and storage in Python programs.

OPERATORS

- **Operators in Python:** Operators are symbols or keywords that perform operations on variables and values in Python. They are used to manipulate and perform actions on data.

- **Arithmetic Operators:** Arithmetic operators are used for mathematical calculations. Examples include:
  - Addition (`+`): Adds two values together.
  - Subtraction (`-`): Subtracts one value from another.
  - Multiplication (`*`): Multiplies two values together.
  - Division (`/`): Divides one value by another.
  - Exponentiation (`**`): Raises a number to a specified power.
  - Modulus (`%`): Returns the remainder of a division.
  - Floor Division (`//`): Returns the quotient of a division, rounded down to the nearest integer.

Understanding and using arithmetic operators is fundamental for performing mathematical calculations and manipulating numerical data in Python programs.

INTRODUCTION TO OPERATORS

- **Division Operator (`/`):** Performs division and returns a floating-point value, even if the result is a whole number. It provides the quotient of a division operation.

- **Modulus Operator (`%`):** Returns the remainder after division. Frequently used in programming and has various applications.

- **String Operators:** 
  - **Addition Operator (`+`):** Concatenates or combines two strings together.
  - **Multiplication Operator (`*`):** Repeats a string a certain number of times. Can work with either a string or a number.

- **Comparison Operators:** Evaluate two variables or values and produce a Boolean result (True or False). Examples include equality (`==`), less than (`<`), greater than (`>`), etc.

- **Logical Operators:** Operate on Boolean values. Examples include "and," "or," and "not." "and" returns true only if both operands are true, "or" returns true if at least one operand is true, and "not" negates the Boolean value.

- **Membership Operators:** "in" and "not in" are used to check whether a value is present in a sequence or not. For example, "in" checks if a number or a string exists in a given list or string.

These operators provide a way to perform various operations and comparisons in Python and can be combined and used in different ways to manipulate and analyze data efficiently. Understanding their concepts and usage is essential for effective programming in Python.

CONTROL FLOW 


- **If Statement:** One of the main types of control flow in programming. It allows you to execute a block of code only if a certain condition is met.
  
- **Usage in Python:** In Python, the syntax for the if statement is straightforward:
  ```python
  a = True
  if a:
      print("It is true.")
  ```
  If the condition (`a` in this case) is true, the indented code under the `if` statement will be executed. Additional code can be added under the `if` statement by further indenting it.
  
- **Else Statement:** You can add an `else` statement to the if statement. The code under the `else` statement will be executed if the condition in the `if` statement is false.
  
Understanding and using the if statement and its variants (`else`, `elif`) is essential for controlling the flow of execution in Python programs based on different conditions.

INTRODUCTION TO CONTROL FLOW

Summary:

- **Indentation in Python:** Indentation is crucial in Python and determines the structure of your program. It is used to denote blocks of code, such as those within loops or conditional statements. Incorrect indentation can lead to syntax errors or unexpected behavior.

- **For Loop:** Used to iterate over a list or any iterable object. In Python, the syntax for a for loop is:
  ```python
  for item in my_list:
      print(item)
  ```
  Here, `item` is a variable representing the current item in the list, and it can be named anything. The loop body is executed for each item in the list.

- **While Loop:** Similar to a for loop but continues looping until a certain condition becomes false. In Python, the syntax for a while loop is:
  ```python
  a = 0
  while a < 5:
      print(a)
      a = a + 1
  ```
  The loop body is executed repeatedly as long as the condition (`a < 5` in this case) is true. It's essential to ensure that the condition will eventually become false to avoid infinite loops.

Understanding how to use loops and correctly manage indentation is crucial for writing structured and readable Python code.


FUNCTIONS

- **Function:** In programming, a function is a reusable block of code that performs a specific task. It takes inputs (arguments) and produces outputs (return values), similar to a machine that transforms inputs into outputs.

- **Analogy:** A common analogy for understanding functions is comparing them to machines, such as a toaster. Just as a toaster takes bread as input and produces toast as output, a function takes input values and produces output values.

- **Input and Output:** Functions can accept zero or more input arguments and can return zero or more output values. Inputs are provided to the function when it is called, and outputs are returned back to the caller.

- **Reusability:** Functions allow for code reusability, meaning you can define a function once and use it multiple times in your program. This promotes modularity and makes code easier to manage and maintain.

Understanding how to define and use functions is fundamental for writing modular, organized, and efficient code in Python and other programming languages.

INTRODUCTION TO FUNCTIONS


- **Function Definition:** In Python, functions are defined using the `def` keyword followed by the function name and arguments in parentheses. The function body is indented and contains the code that performs the desired operation on the inputs.

- **Return Statement:** The `return` keyword is used to specify the output of the function. It can return one or more values. If a function does not explicitly return anything, it implicitly returns `None`.

- **Function Arguments:** Functions can take one or more arguments, which are inputs provided to the function when it is called. These arguments can be used within the function to perform operations or calculations.

- **Returning None:** Functions may or may not return a value. If a function does not return anything explicitly, it returns `None` by default. This is represented by the Python keyword `None`, which signifies the absence of a value.

Understanding how to define functions, specify arguments, and handle return values is essential for writing modular and reusable code in Python. Additionally, recognizing the significance of `None` as a default return value is important for understanding the behavior of functions in Python.

CLASS AND OBJECTS:

- **Expanding Complexity:** As the complexity of a program increases, managing numerous functions and variables for different tasks, such as toasting, baking, microwaving, etc., becomes challenging.

- **Introduction of Classes:** To address this challenge, programmers invented a tool called a class in Python. A class helps label and organize related collections of functions (methods) and attributes (variables).

- **Example: Kitchen Appliances:** For instance, in a kitchen scenario, each appliance like a toaster, microwave, and dishwasher can be represented as a class. Each class would have its own methods (e.g., `toast()`, `bake()`, `microwave()`) and attributes (e.g., `knob_setting`, `power_setting`, `modes`) specific to that appliance.

- **Organizing Code:** Classes help organize code into logical units, making it easier to manage and maintain. They promote code reuse, modularity, and scalability by encapsulating related functionality into a single entity.

- **Application to Larger Systems:** Classes are not limited to representing individual objects; they can also represent larger systems such as entire houses with different rooms, each having various functions and attributes.

Understanding classes and how to use them effectively is essential for building complex and scalable Python programs, enabling developers to organize and manage code in a structured and efficient manner.

INTRODUCTION TO CLASSES AND OBJECTS:


- **Class Definition:** In Python, classes are used to define blueprints for creating objects with specific attributes and methods. Class names typically start with an uppercase letter.

- **Initialization Function (`__init__`):** The `__init__` function is a special method called the initialization function or constructor. It gets called every time an instance of the class is created and initializes the object's attributes.

- **Attributes and Methods:** Attributes are variables associated with a class, while methods are functions associated with a class. These attributes and methods define the behavior and characteristics of objects created from the class.

- **Accessing Attributes and Methods:** Attributes and methods are accessed using the `self` variable, which refers to the specific instance of the class. Inside the class definition, `self` is used to access attributes and call methods.

- **Objects and Instances:** Instances of a class are called objects. Each object has its own set of attributes and can access the methods defined in the class. Multiple objects can be created from the same class, each with its own unique attributes and behavior.

- **Object-Oriented Programming (OOP):** Object-oriented programming is a programming paradigm that revolves around the concept of objects, allowing for better organization, reusability, and scalability of code.

Understanding the concepts and terminology of object-oriented programming, such as classes, objects, attributes, and methods, is essential for building modular, maintainable, and scalable Python programs.

INTENGERS AND FLOATS:

Summary:

- **Integers and Floats:** Integers (`int`) represent whole numbers, while floats (`float`) represent decimal numbers in Python.

- **Interaction:** Integers and floats can interact in Python operations, with Python automatically promoting integers to floats when necessary to preserve precision. For example, in division operations, if one operand is a float, the result will be a float.

- **Conversion:** You can convert between integers and floats using built-in functions:
  - To convert an integer to a float, use the `float()` function.
  - To convert a float to an integer, use the `int()` function. Be aware that converting a float to an integer truncates the decimal part, potentially leading to loss of precision.

- **Common Pitfalls:**
  - Division by zero: Division by zero with integers raises a `ZeroDivisionError`, while division by zero with floats results in either `inf` (positive infinity) or `-inf` (negative infinity).
  - Precision issues: Floats have limited precision due to their representation in binary format, which can lead to rounding errors and unexpected results in mathematical operations.

Understanding how integers and floats interact, how to convert between them, and being aware of common pitfalls is crucial for writing robust and accurate numerical computations in Python.

ALTERNATIVE NUMDER TYPES:

Summary:

- **Conversion with int class:** The int class in Python can convert a string representing a number into an integer. For example, "100" becomes the integer 100.

- **Base Conversion:** The int class can also convert a string from a specified base to base 10. This is achieved by providing a second argument representing the base. For example, "100" in base 2 is equal to 4 in base 10.

- **String Input:** The first argument passed to the int class must always be a string, even when converting from a different base. This is because there may be non-numeric characters in the string that are valid in some bases, but not as integers. For example, "1ab" in base 16 is valid, but "1ab" is not an integer.

Understanding these capabilities of the int class allows for flexible and powerful manipulation of numeric data in Python, particularly when dealing with different number bases. 

INTEGERS:

- **Decimal Class in Python:** Python provides the `decimal` module, which includes the Decimal class. This class is used to represent decimal floating-point numbers with high precision and without the rounding errors associated with floats.

- **Importing the Decimal Class:** To use the Decimal class, you need to import it along with the `getcontext` function from the `decimal` module. This is typically done at the top of your code:

  ```python
  from decimal import Decimal, getcontext
  ```

- **Context Object:** The `getcontext()` function returns a context object that holds global settings for using the Decimal class. This context object can be modified to adjust settings such as precision.

- **Precision:** One important setting that can be modified is the precision, which determines the number of digits to be used in arithmetic operations. By default, the precision is 28 digits, but it can be changed to suit specific needs.

- **Benefits:** Using the Decimal class with appropriate precision settings can help avoid floating-point errors, making it suitable for applications where precision is critical, such as financial calculations.

Understanding how to use the Decimal class and adjust precision settings can improve the accuracy and reliability of numerical computations in Python programs, particularly in scenarios where floating-point errors are problematic, such as financial calculations.

DECIMALS:

- **Decimal Class in Python:** Python provides the `decimal` module, which includes the Decimal class. This class is used to represent decimal floating-point numbers with high precision and without the rounding errors associated with floats.

- **Importing the Decimal Class:** To use the Decimal class, you need to import it along with the `getcontext` function from the `decimal` module. This is typically done at the top of your code:

  ```python
  from decimal import Decimal, getcontext
  ```

- **Context Object:** The `getcontext()` function returns a context object that holds global settings for using the Decimal class. This context object can be modified to adjust settings such as precision.

- **Precision:** One important setting that can be modified is the precision, which determines the number of digits to be used in arithmetic operations. By default, the precision is 28 digits, but it can be changed to suit specific needs.

- **Benefits:** Using the Decimal class with appropriate precision settings can help avoid floating-point errors, making it suitable for applications where precision is critical, such as financial calculations.

Understanding how to use the Decimal class and adjust precision settings can improve the accuracy and reliability of numerical computations in Python programs, particularly in scenarios where floating-point errors are problematic, such as financial calculations.

BOOLEANS:

Booleans, at first glance, seem straightforward: True or False. However, as programmers, we frequently encounter various scenarios where understanding Boolean logic becomes crucial. These scenarios range from simple comparisons to complex conditional statements and logical operations.

In Python, Boolean values are the building blocks of logical expressions and control flow structures like if statements, while loops, and more. Understanding how Boolean operators like AND, OR, and NOT work, as well as their precedence, is essential. Additionally, we encounter truthy and falsy values, where certain non-Boolean values evaluate to True or False in Boolean contexts.

Moreover, there are nuances with comparison operators, especially when dealing with different data types or objects. For instance, equality (==) versus identity (is) comparison, and the behavior of objects like lists or dictionaries in comparisons.

In summary, while Booleans may seem simple, their importance in programming cannot be overstated. A solid understanding of Boolean logic, operators, and their application is fundamental for writing efficient and bug-free code.

STRINGS:


Certainly! In Python, slicing is a powerful technique for working with strings. It allows you to extract a portion of a string by specifying start and end indices. Here's a summary:

1. **Definition**: Slicing in Python refers to the process of extracting a substring from a string.

2. **Syntax**: The syntax for slicing is `string[start_index:end_index]`. This returns the substring starting from `start_index` up to, but not including, `end_index`.

3. **Indexing**: Python strings are zero-indexed, meaning the first character has an index of 0, the second has an index of 1, and so on. Negative indices can also be used to slice from the end of the string.

4. **Example**: Consider the string `example = "Python is awesome"`. To extract the substring "Python", you would use `example[0:6]`, which includes characters from index 0 up to, but not including, index 6.

5. **Omitting Indices**: If you omit the start index, Python assumes it as 0. If you omit the end index, Python assumes it as the length of the string.

6. **Step Argument**: You can also specify a step argument to skip characters while slicing. The syntax is `string[start_index:end_index:step]`.

7. **Immutable**: Slicing does not modify the original string; it returns a new string with the sliced portion.

Overall, slicing is a versatile tool in Python for extracting substrings, making it invaluable for tasks like data parsing and string manipulation.

BYTES:



1. **Definition**: In Python, a bytes object represents an immutable sequence of bytes. It is used to store raw binary data, which can include ASCII characters, Unicode characters, or even non-text binary data.

2. **Purpose**: The bytes object is primarily used for handling raw binary data, where the specific encoding or interpretation of the data is not important. It is commonly used for tasks like streaming files, network communication, or handling binary data formats.

3. **Immutable**: Like strings, bytes objects are immutable, meaning they cannot be modified once created. Operations like slicing or concatenation return new bytes objects rather than modifying the original.

4. **Encoding and Decoding**: While bytes objects store raw binary data, they can be converted to and from strings using encoding and decoding methods (`encode()` and `decode()`). This allows for interoperability between text and binary data when necessary.

5. **Usage**: Some common use cases for bytes objects include reading binary files, sending and receiving data over networks, and interfacing with low-level system functions that deal with binary data.

6. **Literal Syntax**: Bytes objects can be created using a literal syntax by prefixing a sequence of bytes with `b`. For example, `b'hello'` creates a bytes object containing the ASCII representation of the string "hello".

Overall, the bytes object in Python provides a simple and efficient way to work with raw binary data, allowing for flexibility in handling various data formats and communication protocols.















