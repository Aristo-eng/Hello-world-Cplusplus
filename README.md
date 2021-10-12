# Hello, World! C++ Program

C++ "Hello, World!" Program.
C++ is a general purpose programming language that supports procedural, object-oriented and generic programming. C++ Hello, World is the canonical sample for C++, that might be traced back to Kernighan and Ritchie!

# Program description

Every C++ program must have a function known as main(). It is referred to as the entry point for the application when you start execution of the program on your computer. The int portion is the return type of the method. The empty parentheses () after the name indicate that this a function and that it takes no arguments, in other words, there are no parameters for passing in values.

Function bodies in C++ start with an open curly brace.

This code uses cout (pronounced “see out”) to send the text “Hello World!” and a newline/line flush (endl) to the console for output and display. The std:: prefix to these two commands is a way of indicating that they are part of a namespace known as std. The :: is used to indicate that cout and endl are part of the std namespace.

 C++ statements are terminated with semi-colons.

  The return statement is used to end a function when a value is expected to be sent back to a caller. In this case, the caller is the operating system and the value returned is an integer value of 0. If the program reaches this statement, returning a value of 0 is an indication to the operating system that the code executed successfully. Programmers return 0 to indicate successful execution and non-zero values to indicate that an error had occurred in the program somewhere.