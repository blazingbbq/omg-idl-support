# Change Log

All notable changes to the "omg-idl-support" extension will be documented in this file.

## [0.0.1] - 2025-12-16

### Added
- Initial release with comprehensive OMG IDL 4.2 syntax highlighting support
- Support for all IDL type declarations: `struct`, `union`, `enum`, `bitmask`, `bitset`, `interface`, `module`
- Highlighting for primitive types: `long`, `short`, `float`, `double`, `char`, `boolean`, `octet`, etc.
- Extended integer types: `int8`, `int16`, `int32`, `int64`, `uint8`, `uint16`, `uint32`, `uint64`
- Template types: `sequence`, `string`, `wstring`, `fixed`
- Comprehensive annotation support:
  - `@key`, `@optional`, `@id`, `@autoid`
  - `@extensibility`, `@final`, `@appendable`, `@mutable`
  - `@position`, `@bit_bound`, `@value`
  - `@default`, `@default_literal`, `@min`, `@max`, `@range`, `@unit`
  - `@must_understand`, `@non_serialized`
  - `@external`, `@nested`, `@verbatim`
  - `@service`, `@oneway`, `@ami`
- All literal types:
  - Integer literals (hexadecimal, octal, decimal)
  - Floating-point and fixed-point literals
  - String and wide string literals with escape sequences
  - Character and wide character literals
  - Boolean literals (`TRUE`, `FALSE`)
- Operator highlighting: arithmetic, bitwise, and assignment operators
- Preprocessor directive support: `#include`, `#define`, `#ifdef`, `#ifndef`, `#if`, `#elif`, `#else`, `#endif`, `#pragma`
- Comment support: line comments (`//`) and block comments (`/* */`)
- Semantic token mapping for proper theme integration
- Type declaration names highlighted as classes (e.g., struct names, enum names)
- Module names highlighted as namespaces