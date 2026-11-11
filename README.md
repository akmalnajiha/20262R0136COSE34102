## Operating System 

My first commit tryout. 

## Course Overview

Explores how computer systems manage hardware and software resources.

Key topics include:
- Processes and threads
- CPU scheduling
- Process synchronization
- Memory management
- System calls
- Thread
- Virtual memory


## Project 1
## Stack Data Structure

A stack is a data structure that follows the Last In, First Out (LIFO) principle.
The most recently inserted element is removed first.

The main stack operations are:
- Push: Insert an element at the top
- Pop: Remove the top element
- Clear: Remove all elements

## System Calls

System calls allow user-level programs to request services from the operating system kernel.
In this project, I added custom system calls to support stack operations. These system calls allowed a user application to interact with the stack managed inside the Linux kernel.

## Push Operation

The push operation adds a new element to the top of the stack.
During testing, I inserted the following values:
4, 34, 70, 43, 83
After these operations, 83 was the top element because it was inserted last.

## Pop Operation

The pop operation removes the most recently inserted element from the stack.
After inserting five values, I performed three pop operations.
The values were removed in this order:
83, 43, 70
This confirmed that the stack followed the LIFO principle.

## Clear Operation

The clear operation removes all remaining elements from the stack.
After performing three pop operations, two elements remained.
I used the clear operation to remove these remaining elements and reset the stack.

## Testing and Challenges

One challenge was resolving a kernel compilation error. This required checking changes to kernel files and correcting the implementation before rebuilding and testing.

## Reflection
Better understanding of Linux kernel development and system calls.
I learned how to connect user-space applications with kernel-space functionality and how to test custom system calls.
Helped me develop debugging skills and understand the importance of testing when modifying operating system components.
