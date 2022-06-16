# 0x19. C - Stacks, Queues - LIFO, FIFO

This projects covers concepts of Stacks, Queues, LIFO, FIFO implementation. 

# Monty

## Desciption

Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

Monty is a language that aims to close the gap between scripting and programming languages. It relies on a unique stack with specific instructions to manipulate it. By convention, the files containing Monty bytecodes have the .m extension. There is no more than one instruction per line and there can be any number of spaces before or after the opcode and its argument.

# Features

# Opcodes

monty executes the following opcodes:

push
Pushes an element to the stack

pall
Prints all the values on the stack

pint
Prints the value at the top of the stack

pop
Removes the top element of the stack

swap
Swaps the top two elements of the stack

queue
Sets the format of the data to a queue (FIFO)

stack
Sets the format of the data to a stack (LIFO)

nop
Doesn't do anything

add
Adds the top two elements of the stack

sub
Subtracts the top element of the stack from the second top element of the stack

mul
Multiplies the second top element of the stack with the top element of the stack

div
Divides the second top element of the stack by the top element of the stack

mod
Computes the rest of the division of the second top element of the stack by the top element of the stack

pchar
Prints the char at the top of the stack

pstr
Prints the string starting at the top of the stack

rotl
Rotates the stack to the toprotrRotates the stack to the bottom

 

