# EBANX - JavaScript/Node.js Style Guide

## Rules

1. 2 spaces - for indentation
2. Single quotes for strings, for escape, always use template string (ES6) 
3. No unused variables (eslint)
4. ALWAYS use semicolons!
5. Space after keywords `if (condition) { ... }`
6. Space after function name `function foo (args) { ... }`
7. Always use `===` instead of `==`
8. Always use `utf-8`

## Table of Contents

1. [Editor Config](#editor-config)

### Editor Config

Create the file `.editorconfig` and insert at project root folder. 

```
[*.{js,json,es6,coffe,babel,jsx}]
charset = utf-8
end_of_line = lf
indent_size = 2
indent_style = space
insert_final_newline = true
trim_trailing_whitespace = true
```

You can [download the editor config plugin](http://editorconfig.org/#download) to use on your IDE or Text Editor.