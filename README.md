# Java Interpreter (jlox)

This repository contains a Java implementation of an interpreter. The goal of this project is to provide a clear and concise implementation of an interpreter using plain Java, with a focus on simplicity and readability.

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)

## Introduction
The Java Interpreter (jlox) project is a fully functional interpreter implemented in Java. It aims to provide a clear and concise implementation of an interpreter, with a focus on simplicity and readability. The interpreter includes several features, such as:

- Lexical analysis: The interpreter tokenizes the input source code into a sequence of tokens.
- Parsing: The interpreter parses the tokens into an abstract syntax tree (AST) representation.
- Semantic analysis: The interpreter performs semantic analysis on the AST to check for any semantic errors.
- Evaluation: The interpreter evaluates the AST and executes the corresponding actions.

The project follows the principles of crafting interpreters and applies them using plain Java. It serves as a great learning resource for understanding the inner workings of interpreters and how to implement them in Java.

Reference book: [Crafting Interpreters](https://craftinginterpreters.com/).

## Getting Started
Follow these steps to get the interpreter up and running:

1. Clone the repository: `git clone https://github.com/giri-10/jlox
2. Navigate to the project directory: `cd jlox`
3. Build the solution: `javac -d out src/*.java`
4. Run the interpreter: `java -cp out Main`

## Usage
Once the interpreter is running, you can input your own programs or use the already provided test code in test.lox. Explore the source code to gain insights into the interpreter's implementation details.

