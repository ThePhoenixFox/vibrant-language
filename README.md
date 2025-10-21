# Vibrant Programming Language

Vibrant is a programming language that is designed to learn [LLVM](https://llvm.org/). 

## Features

Vibrant has these following features: 

- Strong Static Types\*
- Ahead of Time Compilation\*
- Multiparadigm\*
  - Procedural\*
  - Functional\*
  - Object Oriented\*
 
*\*These features have been scheduled for a future release of the Vibrant specification*

## Version Specification

The Vibrant language specification version is displayed in the following fashion: vM.m:s

`M` is the current major version of the specification, included with every publication

`m` is the current minor version of the specification, included with every publication

`s` is the current status of the specification, only included in this repository's implementation of the specification

Examples: v1.0:5, v2.5, v3.1:4, v4.0

The Vibrant language has specification guideline that updates on every **major** version with the following changes allowed:

### Syntax
- Change existing syntax
- Add new syntax
- Deprecated previous syntax
### Standard Libary
- Change existing specification on the Standard Libary
- Add new functions, objects, and libaries to the Standard Libary
- Deprecate previous functions, objects, and libaries from the Standard Libary

The Vibrant langauge has specification guideline that updates on every **minor** version with the following changes allowed:

### Syntax
- Add new syntax
- Mark for deprecation existing syntax
### Standard Libary
- Add new functions, objects, and libaries to the Standard Libary
- Mark for deprecation existing functions, objects, and libaries from the Standard Libary

This repository contains a **status** for each version of the specification

0. Unusable
1. In development
2. Majority of implementation\*
3. Complete implementation
4. Hotfix\*\*

*\* Has over **75%** of the specification features*

*\*\* May include security, bug, or undefined behavior*

## Build

// TO DO
// CMAKE
// LLVM
// LIBC

## Specification 

You can read the specification for Vibrant [here]()\*. 

*\*// TO DO*

## Sources

These are documentation or articles that have helped in the development of Vibrant

[LLVM](https://llvm.org/)

[Crafting Interpreters](https://craftinginterpreters.com/)

[Creating the Bolt Compiler](https://mukulrathi.com/create-your-own-programming-language/llvm-ir-cpp-api-tutorial/)

