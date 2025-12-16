# OMG IDL Support

Syntax highlighting support for OMG Interface Definition Language (IDL) files in Visual Studio Code.

## Features

This extension provides comprehensive syntax highlighting for OMG IDL 4.2 specification, including:

### Language Constructs
- **Type Declarations**: `struct`, `union`, `enum`, `bitmask`, `bitset`, `interface`, `module`
- **Type Keywords**: Primitive types (`long`, `short`, `float`, `double`, `char`, `boolean`, `octet`, etc.)
- **Extended Types**: `int8`, `int16`, `int32`, `int64`, `uint8`, `uint16`, `uint32`, `uint64`
- **Template Types**: `sequence`, `string`, `wstring`, `fixed`

### Annotations
Full support for standard IDL annotations:
- `@key`, `@optional`, `@id`, `@position`, `@bit_bound`
- `@extensibility`, `@final`, `@appendable`, `@mutable`
- `@default`, `@min`, `@max`, `@range`, `@unit`
- `@non_serialized`, `@must_understand`, `@value`
- And many more...

### Literals and Operators
- **Numeric Literals**: Hexadecimal, octal, decimal, floating-point, and fixed-point
- **String Literals**: Standard and wide strings with escape sequences
- **Character Literals**: Standard and wide characters
- **Boolean Literals**: `TRUE` and `FALSE`
- **Operators**: Arithmetic, bitwise, and assignment operators

### Preprocessor Directives
- `#include` statements (with quoted and angle-bracket formats)
- `#define`, `#ifdef`, `#ifndef`, `#if`, `#elif`, `#else`, `#endif`, `#pragma`

### Comments
- Line comments (`//`)
- Block comments (`/* */`)

## Usage

Simply open any `.idl` file and the extension will automatically provide syntax highlighting.

## Example

```idl
#include "common.idl"

module MyModule {
    @extensibility(MUTABLE)
    struct MyStruct {
        @key long id;
        @optional string name;
        sequence<octet> data;
    };
};
```

## Requirements

No additional requirements or dependencies.

## Extension Settings

This extension does not add any VS Code settings.

## Release Notes

### 0.0.1

Initial release with comprehensive OMG IDL 4.2 syntax highlighting support.
