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

Examples: v1.0:i, v2.5:0, v3.1:x, v4.0:ii

The Vibrant language has specification guideline that updates on every **version** with the following changes allowed:

### Syntax
- Change existing syntax
- Add new syntax
- Deprecated previous syntax
### Standard Library
- Change existing specification on the Standard Library
- Add new functions, objects, and libaries to the Standard Library
- Deprecate previous functions, objects, and libaries from the Standard Library

The Vibrant langauge has implementation guideline that updates on every **minor** version. This repository contains a **status** for each version of the implementation.

| Code | Status Description                     |
|------|----------------------------------------|
| 0    | Unusable (Template)                    |
| i    | In Development                         |
| ii   | Hotfix*                                |
| iii  | Hotfix (OS-specific)*                  |
| iv   | Security Vulnerability**               |
| v    | Security Vulnerability (OS)**          |
| x    | Feature Completion                     |
| xi   | Feature Completion (OS-specific)       |
| xii  | Implementation Completion (OS-specific)|
| xx   | Implementation Completion              |

*\* May include security, bug, or undefined behavior*

*\*\* Retroactive*

## Build

Compiler Requirement

| Compiler | Minimum Version |
|----------|-----------------|
| Clang    | 5.0+ (10+ on macOS) |
| GCC      | 7.4+             |
| MSVC     | 2019 (16.8+)     |

Minimum  Standard Requirement

| Language | Minimum Standard |
|----------|------------------|
| C++      | C++17            |
| C        | C17              |

1. Clone the repository

`git clone <path> https://github.com/ThePhoenixFox/vibrant-language.git`

2. Install [LLVM](https://releases.llvm.org/)
3. Use [CMake](https://cmake.org/download/) for the Vibrant compiler,

```
cd <path>
mkdir build && cd build
cmake ..
```

4. Build the Vibrant compiler
```
-DVIBRANT_BUILD // Builds the Vibrant compiler (Default: ON)
-DVIBRANT_BUILD_TESTS // Build the tests (TO DO) (Default: OFF)
-DVIBRANT_COMPILER_PATH // Path to the compiler source files (Default: vibrant/compiler)
-DVIBRANT_TEST_PATH // Path to the test source files (Default: vibrant/tests)
-DVIBRANT_BUILD_STRICT // Enables -Wall -Werror or /W4 /permissive- (Default: ON)
-DVIVRANT_BUILD_OPTIONS // Extra build options you can put in like -fno-rtti (Default: None)
-DCMAKE_BUILD_TYPE // Debug Release RelWithDebInfo MinSizeRel (Default: Release)
```

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

