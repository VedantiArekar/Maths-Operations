# Maths-Operations

The C arithmetic operators are the symbols that are used to perform mathematical operations on operands. There are a total of 9 arithmetic operators in C to provide the basic arithmetic operations such as addition, subtraction, multiplication, etc.

Types of Arithmetic Operators in C
The C Arithmetic Operators are of two types based on the number of operands they work. These are as follows:

1. Binary Arithmetic Operators

// C program to demonstrate syntax of binary arithmetic

// operators
#include <stdio.h>
 
int main()

{
  
  int a = 10, b = 4, res;
 
    // printing a and b
    printf("a is %d and b is %d\n", a, b);
 
    res = a + b; // addition
    printf("a + b is %d\n", res);
 
    res = a - b; // subtraction
    printf("a - b is %d\n", res);
 
    res = a * b; // multiplication
    printf("a * b is %d\n", res);
 
    res = a / b; // division
    printf("a / b is %d\n", res);
 
    res = a % b; // modulus
    printf("a %% b is %d\n", res);
 
    return 0;
}

Output:

a is 10 and b is 4

a + b is 14

a - b is 6

a * b is 40

a / b is 2

a % b is 2
