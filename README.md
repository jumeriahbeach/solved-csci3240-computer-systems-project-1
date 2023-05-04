Download Link: https://assignmentchef.com/product/solved-csci3240-computer-systems-project-1
<br>
Write a C program that takes a single command-line argument and produces the same output as the xxd program with just that same argument.

A sample test would look like this:

./p1 some_filename

and would produce the same output as this:

xxd some_filename

Note that the C function isprint(3) could prove quite useful here.

Also note, that the language used by the textbook and this class are C without the C++ extensions.

Use turnin to submit just the C program file.

(We will turnin archive files later in the semester.)

To test the project, I will do something like this:rm -rf p1rm -f *.occ -o p1 p1.c./p1 filename ## I may do this for multiple filenames