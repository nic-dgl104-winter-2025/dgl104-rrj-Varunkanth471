
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MMj2nZMu)
# Rsearch and Reflection Journal
Research and Reflection Journal for DGL 104 course

# FUNCTIONAL PARADIGM

- **Lecture Note:**
  - Part of the declarative paradigm, contrasts with imperative (OOP) paradigm.
  - Specifies what a program should do, not how.
  - Valuable in OOP languages (e.g., Kotlin, Swift, Java, JavaScript) via functional tools.
  - Not pure functional languages, but functional-style APIs for collections (arrays, lists).

- **Task Example: Extract Even Numbers from a List (e.g., [1, 2, 3, 4, 5, 6]):**
  - **Imperative (OOP):**
    - Uses `while` loop, `if` statement, and counter (e.g., `count++`).
  - **Functional:**
    - Uses `filter` method with a predicate (e.g., `list.filter { it % 2 == 0 }`).
  - Functional reduces complexity and side effects.

- **Imperative vs. Declarative Paradigms:**
  - **Imperative:**
    - Specifies how (e.g., loops, `if` statements).
    - Linear, step-by-step execution.
  - **Declarative:**
    - Specifies what (e.g., `filter` defines outcome).
    - Compact, avoids explicit flow control.

- **Benefits:**
  - Reduces side effects, improving reliability and readability.

- **Pure Functional Language Qualities:**
  - **Deterministic Functions:**
    - Same input always yields same output.
    - Example: Imperative loop with external `count` fails this (varies per run).
  - **Higher-Order Functions:**
    - Functions that take/return functions (e.g., `filter`, `map`).
    - Example: `calculate(x, y, operation)` applies passed operation.
  - **Recursion:**
    - Functions call themselves instead of loops.
    - Example: Fibonacci (`fib(n) = fib(n-1) + fib(n-2)`) with base cases.
