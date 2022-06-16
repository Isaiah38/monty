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

# The Monty program

To compile all files:

$ gcc -Wall -Werror -Wextra -pedantic *.c -o monty $

1. *Usage: monty file

where file is the path to the file containing Monty byte code

2. If the user does not give any file or more than one argument to your program, print the error message USAGE: monty file, followed by a new line, and exit with the status EXIT_FAILURE

3. If, for any reason, it's not possible to open the file, the program prints the error message Error: Can't open file , followed by a new line, and exit with the status EXIT_FAILURE
.where is the name of the file.

4. If the file contains an invalid instruction, the program prints the error message L<line_number>: unknown instruction , followed by a new line, and exit with the status EXIT_FAILURE
. where <line_number> is the line number where the instruction appears.
. Line numbers always start at 1.

5. The monty program runs the bytecodes line by line and stop if either:
. it executed properly every line of the file.
. it finds an error in the file.
. an error occured

6. If the program can't malloc anymore, the error message Error: malloc failed is printed, followed by a new line, and exit with status EXIT_FAILURE.

7. Only malloc and free are used to manage heap memory.
