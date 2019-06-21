# EBANX - CSS Style Guide

## Rules
1. 2 spaces - for indentation
2. One rule per line
3. Space between rules and brackets

Good
```css
.rule {
  color: #fff;
}

.block,
.item {
  padding: 1em;
}
```

Bad
```
.rule{
  color: #fff;
}

.rule{ background-color: red; }

.block, .item{
  padding: 1em;
}
```

## Table of Contents

1. [Editor Config](#editor-config)
2. [Related](#related)

### Editor Config

Create the file `.editorconfig` and insert at project root folder. 

```
[*.{css}]
indent_style = space
indent_size = 2
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true
```

### Related

Those approaches are always welcome:

- [BEM](http://getbem.com/)
- [ITCSS](https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/)
- [rscss](https://rscss.io/)
