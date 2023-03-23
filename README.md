#Monty
---
The goal of this project is to create an interpreter for Monty ByteCodes files using the C language. 
The data structures in play are stacks and queues.
To understand how stacks work have a look at:
[Differences between stack and queue data stuctures](https://byjus.com/gate/difference-stack-and-queue-data-structures/)

[How do I use extern to share variables between source files in C?](https://stackoverflow.com/questions/1433204/how-do-i-use-extern-to-share-variables-between-source-files)

##The Monty language
---
Monty 0.98 is a scripting language that is first compiled into Monty byte code(Just like Python).It relies on a unique stack, with specific instructions to manipulate it.

##Monty bytecode files
---
Files containing Monty byte codes usually have the .m extension.
Most of the industry uses this standard but it is not required by the specification of the language.
There is not more than one instruction per line. 
There can be any number of spaces before or after the opcode and its argument.
Monty byte code files can contain blank lines (empty or made of spaces only) and any additional text after the opcode or its required argument is not taken into account. 

##Getting started
---
The code is compiled using a gcc compiler thus, it should be installed in your computer.
To install GCC in your system:

> $ sudo apt update && sudo apt upgrade -y
> $ sudo apt install build-essential
> $ sudo apt install manpages-dev 

To check if it is installed:

> $gcc --version

. Clone this repository on your local machine

> git@github.com:lorens247/monty.git

. Compile the code with

> $ gcc -Wall -Werror -Wextra -pedantic -std=c90 *.c -o monty

Any output is printed on stdout and any error message is printed on stderr

## Authors/Collaborators
[Lawrence Ikhidero](https://github.com/lorens247) || [Ruth Mensire](https://github.com/mensirer)


