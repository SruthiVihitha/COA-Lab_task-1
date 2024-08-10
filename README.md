
**README - Lab Assignment 1: Computer Organization and Architecture**

This assignment includes two assembly language programs:

1. **Program to Print "Hello World":**
   - The program starts by setting up a message "Hello World!" followed by a carriage return and a line feed.
   - The message is stored in memory and displayed using DOS interrupt `21h` with function `09h`.
   - The program waits for a keypress before exiting using interrupt `16h`.

2. **Program to Print Your Name ("Sruthi"):**
   - Similar to the first program, this code sets up a message "Sruthi!" and displays it.
   - It utilizes the same DOS interrupt `21h` with function `09h` for output.
   - The program waits for a keypress before terminating.

Both programs are assembled to run starting at memory location `100h`.

