# Bit-Level Systems Programming (C)

This project contains solutions for complex systems programming challenges centered on low-level data representation and bitwise operations.

## Overview
The goal is to implement functions that perform bit-level manipulations using a highly restricted subset of the C programming language. The challenges focus on:
* **Bit Manipulation:** Using only bitwise operators (`&`, `|`, `~`, `^`, `<<`, `>>`) to solve logic puzzles.
* **Two's Complement Arithmetic:** Implementing operations like integer overflow detection and absolute value without using standard arithmetic operators.
* **Floating Point Representation:** Handling IEEE 754 single-precision floating-point bit patterns, including special cases like NaN and infinity.

## Key Challenges Solved
* `byteSwap`: Swapping specific bytes within a 32-bit integer.
* `addOK`: Detecting integer addition overflow using only bitwise logic.
* `float_abs`: Calculating the absolute value of a floating-point number at the bit level.

## Tech Stack
* **Language:** C
* **Core Concepts:** Binary Arithmetic, Memory Management, Bitwise Logic, IEEE 754 Standards
