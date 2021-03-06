# Chapter 1: C++ Basics

## 1.1 Statements and Structure of a program

### Statements:
- A computer program is a sequence of instructions that tell the computer what to do. 
A **statement** is a type of instruction that causes the program to perform some action.
- Most (but not all) statements in C++ end in a semicolon. 
If you see a line that ends in a semicolon, it’s probably a statement.
- There are many different kinds of statements in C++:
    1. Declaration statements
    2. Jump statements
    3. Expression statements
    4. Compound statements
    5. Selection statements (conditionals)
    6. Iteration statements (loops)
    7. Try blocks

### Function and main of the program:
- In C++, statements are typically grouped into units called functions. 
A **function** is a collection of statements that executes sequentially.

### Dissecting Hello world!:
```c++
#include <iostream>
 
int main()
{
   std::cout << "Hello world!";
   return 0;
}
```
- Line 1 is a special type of line called a **preprocessor directive**. This preprocessor directive indicates that we would like to use the contents of the iostream library, which is the part of the C++ standard library that allows us to read and write text from/to the console. We need this line in order to use std::cout on line 5. Excluding this line would result in a compile error on line 5, as the compiler wouldn’t otherwise know what std::cout is.
- cout stands for **character output**
- Line 6 is a return statement. When an executable program finishes running, the program sends a value back to the operating system in order to indicate whether it ran successfully or not. This particular return statement returns the value of 0 to the operating system, which means “everything went okay!”.

### Syntax and syntax errors:
- Rules about how your programs must be constructed in order to be considered valid is called **syntax**.
- When you compile your program, the compiler is responsible for making sure your program follows the basic syntax of the C++ language. If you violate a rule, the compiler will complain when you try to compile your program, and issue you a **syntax error**.
---

## 1.2 Comments

### Single-line comments:
- The // symbol begins a C++ single-line comment, which tells the compiler to ignore everything from the // symbol to the end of the line.

### Multi-line comments:
- The /* and */ pair of symbols denotes a C-style multi-line comment. Everything in between the symbols is ignored.

### Proper use of comments:
Typically comments should be used for three things.
1. For a given library, program, or function, comments are best used to describe *what* the library, program, or function, does. These are typically placed at the top of the file or library, or immediately preceding the function.
2. *Within* a library, program, or function described above, comments can be used to describe *how* the code is going to accomplish its goal.
3. At the statement level, comments should be used to describe *why* the code is doing something. A bad statement comment explains *what* the code is doing.

Programmers often have to make a tough decision between solving a problem one way, or solving it another way. Comments are a great way to remind yourself (or tell somebody else) the reason you made one decision instead of another.

Comment your code liberally, and write your comments as if speaking to someone who has no idea what the code does. Don’t assume you’ll remember why you made specific choices.

### Summary:
- At the library, program, or function level, use comments to describe *what*.
- Inside the library, program, or function, use comments to describe *how*.
- At the statement level, use comments to describe *why*.

---

## 1.3 Introduction to Variables




