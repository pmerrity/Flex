# Flex
Flex is a responsive grid system. It is based on a 24-column grid system and contains standard media query breakpoints for mobile (480px) and tablet (768px), so you don't have to worry about it!

### Features
- Whopping 1kb
- Breakpoints at 480px, 600px, 768px, and 992px

### Syntax
The grid is light and simple to master! There are 5 classes you can use:
- .row -- A wrapper that is clearfix ready (prevents collapsing when children are floated).
- .col-# -- Replace "#" with a number 1 - 24 to determine number of columns it spans. (i.e. col-24 = 100%)
- .no-float -- Overrides the "float: left" property in each .col-# class. Use with .auto-margin
- .auto-margin -- Makes an element block-level and centers it within the parent. Example: maybe you want an element to be 50%, but  centered instead of to the left
- .pull-right -- Columns float left by default. Want it on the right? Use this.
