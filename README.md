# Revision: C++

C++ from the scratch
- [LearnCpp.com](https://www.learncpp.com/)

Useful links for programming C++ in VSCode IDE on Linux
- [C/C++ for Visual Studio Code](https://code.visualstudio.com/docs/languages/cpp)
- [Using C++ on Linux in VS Code](https://code.visualstudio.com/docs/cpp/config-linux)

---

## Rules:
- Every C++ program must have a special function named main (all lower case letters). 
When the program is run, execution starts with the first statement inside of function main and then continues sequentially.

## Best Practices:
- Name your code files name.cpp, where name is a name of your choosing, and .cpp is the 
extension that indicates the file is a C++ source file.
- Create a new project for each new program you write.
- Use the debug build configuration when developing your programs. When you’re ready to 
release your executable to others, or want to test performance, use the release build configuration.
- Disable compiler extensions to ensure your programs (and coding practices) remain compliant 
with C++ standards and will work on any system.
- Don’t let warnings pile up. Resolve them as you encounter them (as if they were errors).
- Turn your warning levels up to the maximum, especially while you are learning. It will help you identify possible issues.
- Comment your code liberally, and write your comments as if speaking to someone who has no idea what the code does. Don’t assume you’ll remember why you made specific choices.
- 

## Warnings:
- Don’t use multi-line comments inside other multi-line comments. Wrapping single-line comments inside a multi-line comment is okay.
- 

## Keep in mind:
- For GCC/G++, you can pass compiler flags -std=c++11, -std=c++14, -std=c++17, or -std=c++2a 
to enable C++11/14/17/2a support respectively.
- If you ever write code that is so complex that needs a comment to explain what a statement is doing, you probably need to rewrite your statement, not comment it.
- 

## Useful Ubuntu commands
- To check the default c++ compiler standard in ubuntu terminal: `g++ -dM -E -x c++  /dev/null | grep -F __cplusplus`
- 

---

### What is C++ good at?
C++ excels in situations where high performance and precise control over memory and other resources is needed. Here are a few common types of applications that most likely would be written in C++:
- Video games
- Real-time systems (e.g. for transportation, manufacturing, etc…)
- High-performance financial applications (e.g. high frequency trading)
- Graphical applications and simulations
- Productivity / office applications
- Embedded software
- Audio and video processing

### Developing C++ programs: Simplistic approach

![image](https://github.com/Rupak1432/cpp/blob/master/Images/Development.png)


