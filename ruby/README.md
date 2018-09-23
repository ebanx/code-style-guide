# EBANX - Ruby Style Guide

## Rules
1. Use `UTF-8` for encoding
2. Use two spaces (soft tabs) for identation
3. Use `snake_case` for variables and methods
4. Use `PascalCase` for classes and modules
5. Use `UPPER_PASCAL_CASE` for constants
6. Never use `camelCase`
7. Use `?` at the end of the name of methods that returns boolean values, e.g.: `active?`, `valid?`
8. Never rescue `Exception` without rethrowing, if so, prefer `StandardError`. That's because `Exception` is the root of all ~~evil~~ exceptions, such as `SyntaxError`
9. Omit parentheses on method calls when the method doesn't take arguments

## Table of Contents
