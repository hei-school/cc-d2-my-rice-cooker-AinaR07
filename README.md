# Interactive Rice Cooker Program
# Overview

This TypeScript program simulates an interactive rice cooker with various cooking options. It provides a menu, allows the user to select cooking methods, simulates the cooking process, and displays corresponding messages in the console.

# Features

Menu Display: The program presents a menu with multiple cooking options.
Option Selection: Users can choose an option by entering a number between 1 and 8.
Cooking Simulation: Each selected option simulates a cooking process and displays relevant messages in the console.
Prerequisites
Before running the program, ensure you have Node.js installed.

# Setup
Install Dependencies: Execute the following command in your terminal to install required dependencies:

bash:

npm install readline
Run the Program: To start the rice cooker program, run the following command:

bash:

node index.ts

## Linter Setup
The program can be linted using ESLint for TypeScript. Follow these steps to set up ESLint:

Install ESLint Globally:

bash:

npm install -g eslint
Install TypeScript ESLint:

bash:

npm install @typescript-eslint/parser @typescript-eslint/eslint-plugin --save-dev
Run Linter:

To lint your TypeScript code, execute:

bash:

npx eslint --fix index.ts (automatic correction)

npx eslint index.ts

This command will check for any potential issues or coding style violations in your TypeScript code.

