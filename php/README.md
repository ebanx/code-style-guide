# EBANX - PHP Style Guide

## Rules

We are following the [PHP PSR-2 Coding Standards](http://www.php-fig.org/psr/psr-2/):

1. Code MUST follow a "coding style guide" PSR [[PSR-1]].
2. Code MUST use 4 spaces for indenting, not tabs.
3. There MUST NOT be a hard limit on line length; the soft limit MUST be 120 characters; lines SHOULD be 80 characters or less.
4. There MUST be one blank line after the `namespace` declaration, and there MUST be one blank line after the block of `use` declarations.
5. Opening braces for classes MUST go on the next line, and closing braces MUST go on the next line after the body.
6. Opening braces for methods MUST go on the next line, and closing braces MUST go on the next line after the body.
7. Visibility MUST be declared on all properties and methods; `abstract` and `final` MUST be declared before the visibility; `static` MUST be declared after the visibility.
8. Control structure keywords MUST have one space after them; method and function calls MUST NOT.
9. Opening braces for control structures MUST go on the same line, and closing braces MUST go on the next line after the body.
10. Opening parentheses for control structures MUST NOT have a space after them, and closing parentheses for control structures MUST NOT have a space before.

## Table of Contents

1. [Editor Config](#editor-config)
2. [Sublime Text 3](#sublime-text-3)

### Editor Config

Create the file `.editorconfig` and insert at project root folder. 

```
[*.php]
charset = utf-8
end_of_line = lf
insert_final_newline = true
trim_trailing_whitespace = true
indent_style = space
indent_size = 4
```

You can [download the editor config plugin](http://editorconfig.org/#download) to use on your IDE or Text Editor.

### Sublime Text 3

If you want to follow PSR-2 on all your projects without a `.editorconfig` you can edit your Syntax Specific Settings on Sublime to be like this:

```
{
    "default_line_ending": "unix",
    "ensure_newline_at_eof_on_save": true,
    "rulers":
    [
        80,
        120
    ],
    "tab_size": 4,
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "word_wrap": "true"
}
```