AIM : To study and implement C++ Program Structure (Data Types)

SOFTWARE USED : VS CODE

1) Theory

In C++, data types define the nature of data a variable can hold. The most commonly used built-in data types include:

int – stores integer values.

float – stores decimal (floating point) values with single precision.

double – stores decimal values with double precision.

char – stores single characters.

bool – stores boolean values (true or false).

This program demonstrates how to:

Declare and initialize variables of each type.

Display their values using cout.

Determine the memory occupied by each data type using the sizeof() operator.

Understanding the behavior and memory requirements of each data type helps in writing efficient code and selecting appropriate types for variables in real-world programs.

2) Algorithm
   
Start the program.

Include the required header file (#include <iostream>).

Use the std namespace or write std::cout.

Declare variables of types: int, float, double, char, and bool.

Initialize these variables with sample values.

Use cout to display each variable's value.

Apply the sizeof() operator to each variable to show memory usage.

End the program.

3) Procedure
 
Create a new C++ source file.

Write the basic structure of a C++ program with #include <iostream> and main() function.

Declare variables of types int, float, double, char, and bool.

Initialize the variables with meaningful sample values.

Use cout statements to print:

The values of each variable.

The memory size of each variable using sizeof().

Compile and run the program.

Observe and analyze the output to understand:

The type of value stored.

The size (in bytes) each data type occupies.

How data behaves and is displayed in C++.

4) Sample Output Observation

Integer variable displays whole number.

Float and double show decimal values (with different precision).

Char shows a single character.

Bool displays either 0 (false) or 1 (true).

Sizes vary based on system architecture, but typically:

int – 4 bytes

float – 4 bytes

double – 8 bytes

char – 1 byte

bool – 1 byte

5) Conclusion
Through this experiment, we gained a clear understanding of built-in data types in C++. It highlighted how different data types are declared,
initialized, displayed, and how much memory each occupies. This foundational knowledge is essential for writing efficient and reliable C++ programs
and making informed decisions when choosing appropriate data types for various computational tasks.
