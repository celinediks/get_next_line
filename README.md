# get_next_line

get_next_line is one of the projects in the curriculum of school 42. This project is about programming a function that returns a line
read from a file descriptor using static variables.

## Project description
<p>Subject document of the project: <a href="en.subject.pdf" target="_blank">get_next_line</a></p>
Repeated calls to the function get_next_line should return text from a file descriptor one line at a time. You should use a single static variable and a buffer_size that decides how many bites we read at one go.
The only allowed external functions to use with this projects are: read, malloc and free.

### Norm writing

This project is written in accordance to the norm of school 42. Some of the most important norm rules are:
- Each function has a maximum of 25 lines
- One single variable declaration per line, all variables on top of the function 
- After the variable declarations, a newline will split them with the rest of the function
- No for loops allowed


## Install and run the project

First, clone my repository on your computer via the green "code" button on top of this page.
All the functions can be compiled using my main.c file.
Create a "test.txt" file with some text of your own choice which my get_next_line function will read from.
You can also choose a buffer size of you own choice, add this in the compiling part at the question marks in "BUFFER_SIZE=??"
- run <code>gcc get_next_line.c get_next_line_utils.c main.c -D BUFFER_SIZE=?? && ./a.out</code> to compile
- to print multiple lines, add some lines of  <code> printf("%s", get_next_line(fd)); </code> in my main.

