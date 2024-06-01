# Project Name
**0x04. UTF-8 Validation**

For the “0x04. UTF-8 Validation” project, you will need to apply your knowledge in bitwise operations, understanding of the UTF-8 encoding scheme, and Python programming skills to validate whether a given dataset represents a valid UTF-8 encoding. Here’s a list of concepts and resources that will be helpful:

### Concepts Needed:

1.  **Bitwise Operations in Python**:
    
    -   Understanding how to manipulate bits in Python, including operations like AND (`&`), OR (`|`), XOR (`^`), NOT (`~`), shifts (`<<`, `>>`).
    -   [Python Bitwise Operators](https://wiki.python.org/moin/BitwiseOperators "Python Bitwise Operators")
2.  **UTF-8 Encoding Scheme**:
    
    -   Familiarity with the UTF-8 encoding rules, including how characters are encoded into one or more bytes.
    -   Understanding the patterns that represent a valid UTF-8 encoded character.
    -   [UTF-8 Wikipedia](https://en.wikipedia.org/wiki/UTF-8 "UTF-8 Wikipedia")
    -   [Characters, Symbols, and the Unicode Miracle](https://www.youtube.com/watch?v=MijmeoH9LT4 "Characters, Symbols, and the Unicode Miracle")
    -   [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/ "The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets")
3.  **Data Representation**:
    
    -   How to represent and work with data at the byte level.
    -   Handling the least significant bits (LSB) of integers to simulate byte data.
4.  **List Manipulation in Python**:
    
    -   Iterating through lists, accessing list elements, and understanding list comprehensions.
    -   [Python Lists](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists "Python Lists")
5.  **Boolean Logic**:
    
    -   Applying logical operations to make decisions within the program.

By studying these concepts and utilizing the resources provided, you will be equipped to tackle the UTF-8 validation project, effectively applying bitwise operations and logical reasoning to determine the validity of UTF-8 encoded data.

##  Requirements

### Python Scripts
*   Allowed editors: `vi`, `vim`, `emacs`.
*   All your files will be interpreted/compiled on Ubuntu 20.04 LTS using gcc, using python3 (version 3.8.5).
*   All your files should end with a new line.
*   The `main.py` files are used to test your functions, but you don’t have to push them to your repo.
*   The first line of all your files should be exactly `#!/usr/bin/python3`.
*   Your code should use the pycodestyle (version `2.8.*`).
*   All your files must be executable.
*   All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`).
*   All your functions (inside and outside a class) should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)`' and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`).
*   A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified).


## Project Description

* **0. UTF-8 Validation** - Write a method that determines if a given data set represents a valid UTF-8 encoding. - `0-stats.py`.

    ```
    carrie@ubuntu:~/0x04-utf8_validation$ ./0-main.py
    True
    True
    False
    carrie@ubuntu:~/0x04-utf8_validation$
    ```
---
