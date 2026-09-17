Simple Shell Proyect

This proyect is a simple UNIX command interpreter that replicates the basic functionality of a shell. It is designed to demosntrate understanding
of process creation, enviroment, manipulation and system calls. This shell programm reads commands from standard input, executes them and displays the output.
This implementation supports executing commands with arguments, handling envioronment variaibles. Both interactive and non interactive modes. Error handling that
matches standard system shell outputs. 

Compilation:
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

Usage
Interactive Mode
./hsh
$ /bin/ls
hsh main.c shell.c
$ exit


Non Interactive Mode
echo "/bin/ls" | ./hsh

Files
main.c: Entry point of shell.
shell.c Core logic for the command loop and input processing
hsh.The final executable
man_1_simple_shell: The manual page for the shell.

Milenys/Shaudi_Lind

