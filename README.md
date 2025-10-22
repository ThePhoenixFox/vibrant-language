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

`M` is the current version of the specification, included with every publication

`m` is the current implementation version of the specification, included with every publication of this repository

`s` is the current status of the implementation, only included in this repository

Examples: v1.0:1, v2.5, v3.1:4, v4.0

The Vibrant language has specification guideline that updates on every **version** with the following changes allowed:

### Syntax
- Change existing syntax
- Add new syntax
- Deprecated previous syntax
### Standard Libary
- Change existing specification on the Standard Libary
- Add new functions, objects, and libaries to the Standard Libary
- Deprecate previous functions, objects, and libaries from the Standard Libary

The Vibrant langauge has implemention guideline that updates on every **minor** version. This repository contains a **status** for each version of the implementation.

- 0. Unusable (Template)
- 1. In development
- 2. Hotfix\*
- 3. Hotfix (OS)*
- 4. Security vulnerability\*\*
- 5. Security vulnerability (OS)\*\*
- 10. Feature Completion
- 11. Feature Completion (OS)
- 12. Implemention Completion (OS)
- 20. Implementation Completion

*\* May include security, bug, or undefined behavior*

*\*\* Retroactive*

## Build

// TO DO
// CMAKE
// LLVM
// LIBC

## Specification 

You can read the specification for Vibrant [here]()\*. 

*\*// TO DO*

## License

Different parts of this repository make use of third party software. You can find license to these software in a respective `LICENSE.txt` file.

LLVM's license is include in the root directory of this repository and is the license this repository uses for its own source code. 

## Sources

These are documentation or articles that have helped in the development of Vibrant

[LLVM](https://llvm.org/)

[Crafting Interpreters](https://craftinginterpreters.com/)

[Creating the Bolt Compiler](https://mukulrathi.com/create-your-own-programming-language/llvm-ir-cpp-api-tutorial/)

