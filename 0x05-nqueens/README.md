# Project Name

**0x05. N Queens**

The “0x05. N queens” project is a classic problem in computer science and mathematics, known for its application of the backtracking algorithm to place N non-attacking queens on an N×N chessboard. To successfully complete this project, you will need to understand several key concepts and have access to resources that will help you grasp the necessary algorithms and techniques.

### Concepts Needed:

1.  **Backtracking Algorithms**:

    - Understanding how backtracking algorithms work to explore all potential solutions to a problem and backtrack when a solution cannot be completed.
    - [Backtracking Introduction](https://www.geeksforgeeks.org/introduction-to-backtracking-data-structure-and-algorithm-tutorials/ "Backtracking Introduction")

2.  **Recursion**:

    - Using recursive functions to implement backtracking algorithms.
    - [Recursion in Python](https://realpython.com/python-thinking-recursively/ "Recursion in Python")

3.  **List Manipulations in Python**:

    - Creating and manipulating lists, especially to store the positions of queens on the board.
    - [Python Lists](https://docs.python.org/3/tutorial/datastructures.html "Python Lists")

4.  **Python Command Line Arguments**:

    - Handling command-line arguments with the `sys` module.
    - [Command Line Arguments in Python](https://docs.python.org/3.3/library/sys.html#sys.argv "Command Line Arguments in Python")

By studying these concepts and utilizing the resources provided, you will be equipped with the knowledge required to implement an efficient solution to the N queens problem using Python. This project not only tests programming and problem-solving skills but also offers an excellent opportunity to learn about algorithmic thinking and optimization techniques.

## Requirements

### Python Scripts

- Allowed editors: `vi`, `vim`, `emacs`.
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS using gcc, using python3 (version 3.8.5).
- All your files should end with a new line.
- The `main.py` files are used to test your functions, but you don’t have to push them to your repo.
- The first line of all your files should be exactly `#!/usr/bin/python3`.
- Your code should use the pycodestyle (version `2.8.*`).
- All your files must be executable.
- All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`).
- All your functions (inside and outside a class) should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)`' and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`).
- A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified).

## Project Description

- **0. N queens** - Write a program that solves the N queens problem. - `0-nqueens.py`.

  ```
  julien@ubuntu:~/0x08. N Queens$ ./0-nqueens.py 4
  [[0, 1], [1, 3], [2, 0], [3, 2]]
  [[0, 2], [1, 0], [2, 3], [3, 1]]
  julien@ubuntu:~/0x08. N Queens$ ./0-nqueens.py 6
  [[0, 1], [1, 3], [2, 5], [3, 0], [4, 2], [5, 4]]
  [[0, 2], [1, 5], [2, 1], [3, 4], [4, 0], [5, 3]]
  [[0, 3], [1, 0], [2, 4], [3, 1], [4, 5], [5, 2]]
  [[0, 4], [1, 2], [2, 0], [3, 5], [4, 3], [5, 1]]
  julien@ubuntu:~/0x08. N Queens$
  ```
