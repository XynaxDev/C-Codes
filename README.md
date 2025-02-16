# C Codes Basic Demonstration

This repository contains a simple basic demonstration of various C code examples covering input/output operations, arithmetic, control structures, loops, and functions. These examples are designed to help beginners understand the fundamentals of C programming.

## Table of Contents
- [Functions](#functions)
- [Loops](#loops)
  - [For Loop](#for-loop)
  - [While Loop](#while-loop)
  - [Do-While Loop](#do-while-loop)
- [Conditional Statements](#conditional-statements)
  - [If-Else](#if-else)
  - [Switch-Case](#switch-case)
  - [Ternary Operator](#ternary-operator)
- [Input/Output](#inputoutput)
- [Arithmetic Operations](#arithmetic-operations)
- [Compilation](#compilation)
- [Execution](#execution)
---

## Functions

**Syntax:**
```c
// Function prototype (optional)
return_type functionName(parameter_list);

// Function definition
return_type functionName(parameter_list) {
    // Code block
    return value; // if needed
}
```

**Example:**
```c
int add(int a, int b) {
    return a + b;
}
```

---

## Loops

### For Loop

**Syntax:**
```c
for (initialization; condition; increment) {
    // Code block
}
```

**Example:**
```c
for (int i = 1; i <= 10; i++) {
    printf("%d ", i);
}
```

### While Loop

**Syntax:**
```c
while (condition) {
    // Code block
}
```

**Example:**
```c
int i = 1;
while (i <= 10) {
    printf("%d ", i);
    i++;
}
```

### Do-While Loop

**Syntax:**
```c
do {
    // Code block
} while (condition);
```

**Example:**
```c
int i = 1;
do {
    printf("%d ", i);
    i++;
} while (i <= 10);
```

---

## Conditional Statements

### If-Else

**Syntax:**
```c
if (condition) {
    // Code block if true
} else {
    // Code block if false
}
```

**Example:**
```c
if (a < b) {
    printf("a is smaller than b");
} else {
    printf("a is not smaller than b");
}
```

### Switch-Case

**Syntax:**
```c
switch(expression) {
    case constant1:
        // Code block
        break;
    case constant2:
        // Code block
        break;
    default:
        // Code block if no case matches
}
```

**Example:**
```c
switch(day) {
    case 1: printf("Monday"); break;
    case 2: printf("Tuesday"); break;
    // ...
    default: printf("Invalid day");
}
```

### Ternary Operator

**Syntax:**
```c
condition ? expression_if_true : expression_if_false;
```

**Example:**
```c
int min = (a < b) ? a : b;
```

---

## Input/Output

**Syntax:**
```c
// Output
printf("format string", variables);

// Input
scanf("format string", &variables);
```

**Example:**
```c
int age;
printf("Enter your age: ");
scanf("%d", &age);
printf("Your age is %d\n", age);
```

---

## Arithmetic Operations

**Syntax:**
```c
// Addition, subtraction, multiplication, division
int sum = a + b;
int difference = a - b;
int product = a * b;
int quotient = a / b;
```

**Example:**
```c
int a = 5, b = 3;
printf("Sum: %d\n", a + b);
```
## Compilation

To compile the code, use a C compiler (e.g., GCC):
```bash
gcc C_Language_Basics.c -o basics
```
## Execution

After successful compilation, run the executable from your terminal:
```bash
./basics
```
<p align = "center" > Thank you for exploring this basic demonstration of C codes. 
We hope this repository serves as a useful resource in your journey to learning C programming.
Happy Coding!😊 </p>
