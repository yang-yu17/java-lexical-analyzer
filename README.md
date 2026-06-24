# java-lexical-analyzer
DFA-based lexical analyzer implemented in Java for compiler front-end tokenization.

## Overview

A lexical analyzer (lexer) implemented in Java using Deterministic Finite Automata (DFA).

This project scans source code and converts character streams into tokens used by later stages of a compiler.

Developed as part of a Programming Languages course at Queens College.

---

## Features

Supported token types:

* Identifiers
* Integer literals
* Floating-point literals
* Arithmetic operators
* Comparison operators
* Assignment operators
* Parentheses
* Braces
* Reserved keywords

Supported keywords include:

* IF
* ELSE
* REPEAT
* TIMES
* UNTIL
* PROCEDURE
* RETURN
* DISPLAY
* INPUT
* RANDOM
* AND
* OR
* NOT

---

## Technologies

* Java
* DFA (Deterministic Finite Automata)
* Lexical Analysis
* Compiler Design

---

## Files

### Source Code

* Lexer.java
* IO.java
* LexerExample.java

### Test Cases

Input and output files are included for validation and testing.

---

## Example

Input:

IF x >= 10
DISPLAY x

Output:

IF
IDENT(x)
GE
INT(10)
DISPLAY
IDENT(x)

---

## Learning Outcomes

* Finite State Machine design
* DFA implementation
* Token recognition
* Compiler front-end concepts
* Lexical analysis algorithms

---

## Author

Yuyan Yang

