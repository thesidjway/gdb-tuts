The following commands are the ones used most frequently:

1. b main - Puts a breakpoint at the beginning of the program
2. b - Puts a breakpoint at the current line
3. b N - Puts a breakpoint at line N
4. b +N - Puts a breakpoint N lines down from the current line
5. b fn - Puts a breakpoint at the beginning of function "fn"
6. d N - Deletes breakpoint number N
7. info break - list breakpoints
8. r - Runs the program until a breakpoint or error
9. c - Continues running the program until the next breakpoint or error
10. f - Runs until the current function is finished
11. s - Runs the next line of the program
12. s N - Runs the next N lines of the program
13. n - Like s, but it does not step into functions
14. u N - Runs until you get N lines in front of the current line
15. p var - Prints the current value of the variable "var"
16. bt - Prints a stack trace
17. u - Goes up a level in the stack
18. d - Goes down a level in the stack
19. q - Quits gdb
