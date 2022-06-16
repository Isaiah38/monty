# 0x19. C - Stacks, Queues - LIFO, FIFO

This projects covers concepts of Stacks, Queues, LIFO, FIFO implementation. 

# Monty

## Desciption

Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

Monty is a language that aims to close the gap between scripting and programming languages. It relies on a unique stack with specific instructions to manipulate it. By convention, the files containing Monty bytecodes have the .m extension. There is no more than one instruction per line and there can be any number of spaces before or after the opcode and its argument.

# Features

# Opcodes

monty executes the following opcodes:

1. push
Pushes an element to the stack

2. pall
Prints all the values on the stack

3. pint
Prints the value at the top of the stack

4. pop
Removes the top element of the stack

5. swap
Swaps the top two elements of the stack

6. queue
Sets the format of the data to a queue (FIFO)

7. stack
Sets the format of the data to a stack (LIFO)

8. nop
Doesn't do anything

9. add
Adds the top two elements of the stack

10. sub
Subtracts the top element of the stack from the second top element of the stack

11. mul
Multiplies the second top element of the stack with the top element of the stack

12. div
Divides the second top element of the stack by the top element of the stack

13. mod
Computes the rest of the division of the second top element of the stack by the top element of the stack

14. pchar
Prints the char at the top of the stack

15. pstr
Prints the string starting at the top of the stack

16. rotl
Rotates the stack to the toprotrRotates the stack to the bottom

 

