# Data Structures and ALgorithms

This README provides a brief overview of different Data Structures and Algorithms.

## Object-Oriented Programming (OOP)

Object-Oriented Programming is a programming paradigm that organizes code around objects, which encapsulate data and behavior. Key concepts include:
- **Encapsulation:** Bundling data and methods into a single unit.
- **Inheritance:** Allows a class to inherit properties and behaviors from another class.
- **Polymorphism:** Objects of different types can be treated as objects of a common base type.
- **Abstraction:** Simplifying complex systems by modeling essential features.

## Procedural Programming

Procedural Programming organizes code as a series of procedures or functions. Key characteristics include:
- Sequences of instructions executed one after another.
- Data is often shared among procedures.
- Emphasis on procedures that operate on data.

## Functional Programming

Functional Programming treats computation as the evaluation of mathematical functions. Key principles include:
- Immutability: Once data is created, it cannot be changed.
- First-class functions: Functions can be assigned to variables and passed as arguments.
- Higher-order functions: Functions that take other functions as parameters.

## Static vs. Dynamic Languages

### Static Languages

Static languages perform type checking at compile-time, and the association between variable names and types is set during compilation. Examples include C, C++, and Java.

### Dynamic Languages

Dynamic languages perform type checking at runtime, and the association between variable names and types is set during program execution. Examples include Python, JavaScript, and Ruby.

## Compile Time vs. Runtime

### Compile Time

Compile time refers to the phase when the source code is translated into machine code or an intermediate code by a compiler. Activities include type checking and syntax checking. Compile-time errors are detected before execution.

### Runtime

Runtime is the phase when the compiled program is running and performing tasks. Activities include executing instructions and processing data. Runtime errors may occur during program execution.


## Stack

### Memory Allocation

- **Automatic Allocation:** Memory is automatically allocated and deallocated as functions are called and return.
- **LIFO (Last-In-First-Out):** The most recently called function's variables are stored at the top of the stack.

### Scope

- **Local Variables:** Typically used for local variables within functions.
- **Limited Lifetime:** Variables have a limited lifetime, tied to the scope of the function they belong to.

### Access Speed

- **Faster Access:** Memory access is faster since it involves moving the stack pointer up and down.

### Size Limitations

- **Limited Size:** The size of the stack is usually limited, and exceeding it can lead to a stack overflow.

### Thread-specific

- **Per Thread:** Each thread of execution has its own stack.

### Usage

- **Method Calls:** Used for managing function calls and local variables.
- **Efficiency:** Generally more efficient for managing memory with a known and limited scope.

## Heap

### Memory Allocation

- **Manual Allocation:** Memory is manually allocated and deallocated.
- **Dynamic Allocation:** Allows for dynamic memory allocation during runtime.

### Scope

- **Global Variables:** Typically used for global variables and objects that need a longer lifetime.
- **Extended Lifetime:** Variables can persist beyond the scope of the functions that created them.

### Access Speed

- **Slower Access:** Memory access is relatively slower since it involves locating a free block of memory and updating memory allocation tables.

### Size Limitations

- **Dynamic Size:** The size of the heap is more flexible and can grow as needed (limited by available system memory).

### Shared among Threads

- **Shared Space:** Heap memory is shared among all threads in a program.

### Usage

- **Dynamic Data:** Used for managing data with an unknown or variable runtime size.
- **Flexibility:** Provides more flexibility for managing memory at runtime.
 
 
# Summary For the day
## Procedural Language

- **Definition:** Specifies a series of well-structured steps and procedures to compose a program, involving statements, functions, and commands.

## Functional Language

- **Definition:** Involves writing a program solely in pure functions, bundling code together for reuse, emphasizing creating new data without modifying original variables.

## Object-Oriented Programming (OOP)

- **Definition:** Focuses on dividing code into objects, combining code and data to form objects, allowing for easier development, debugging, reuse, and maintenance of software.

## Static vs. Dynamic Languages

- **Definition:** Static languages perform type checking at compile time, requiring variable types to be specified in advance. Dynamic languages perform type checking at runtime, allowing flexibility in changing variable types during execution.

## Dynamic Language Behavior

- **Definition:** In dynamic languages like Python, changing variable types during runtime doesn't result in compile-time errors, as types are determined during program execution.

## Variables in Static Languages

- **Definition:** Variables in static languages must be assigned a data type, and changing types leads to compile-time errors.

## Data Type Declaration

- **Definition:** Declaring data types before usage provides more control and reduces runtime errors in static languages.

## Dynamic Language Convenience

- **Definition:** Dynamic languages don't require specifying data types, saving coding time, but may lead to runtime errors.

## Memory Management

- **Definition:** Memory management involves stack and heap memory. Variables are in the stack, and actual values are in the heap.

## Multiple Reference Variables

- **Definition:** Multiple reference variables can point to the same object; changes in one variable reflect in others pointing to the same object.


