#Langage C

# My Rice Cooker Program - Rice Cooking Simulator

# Overview

This program simulates a rice cooker with various cooking options. It allows the user to select different cooking methods, simulates the cooking process, and displays corresponding messages in the console.

# Features

Menu Display: The program presents a menu offering multiple cooking options.
Option Selection: Allows the user to choose an option by entering a number between 1 and 8.
Cooking Simulation: Each selected option simulates a cooking process and displays relevant messages in the console.
This C language program simulates a simple rice cooker, offering various cooking options.

# Instructions
# How to Run

To compile and run the program, you can use a C compiler such as GCC:
Compilation: Use a C compiler such as GCC (GNU Compiler Collection) to compile the source code.

bash:

gcc -o RC.c

main.c: Name of the C source code file.
Execution: Once compiled successfully, run the program using the following command:

bash:

./RC c
Ensure you are in the directory containing your program or specify the full path if it's located elsewhere.

Running Static Code Analysis
You can use tools like cppcheck for static code analysis to check for potential issues or bugs in your C code.

# Linting with cppcheck

bash:

cppcheck RC.c
Make sure cppcheck is installed on your system before running the analysis.
