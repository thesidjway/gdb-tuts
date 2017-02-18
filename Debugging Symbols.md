A Debugging Symbol Table maps instructions in the compiled binary program to their corresponding variable, function, or line in the source code. 

If you plan to debug your program, then it is required to create a symbol table which will have the required information to debug the program

1. A symbol table works for a particular version of the program – if the program changes, a new table must be created.
2. Debug builds are often larger and slower than retail (non-debug) builds; debug builds contain the symbol table and other ancillary information.
3. If you wish to debug a binary program you did not compile yourself, you must get the symbol tables from the author.

We need to compile with the -g flag as shown below:

# gcc -g hello.cc -o hello 


