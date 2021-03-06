# Sass Guide

A collection of Sass best practices

## Syntax & Formatting

Two spaces for indent, no tabs

Max 80-characters per line

Open bracket on same line as selector; close bracket on its own line

One rule per line

No space before colon; one space after

Blank line between selector blocks

## Sass features

Use of variables, @extend and @include

Maximum three levels of nesting

Modifiers and pseudo-selectors as child rules: hover, active, focus

Responsive: breakpoints, media query mixins

## Architecture

base

  - Variables, colors, typography

patterns

  - Buttons, carousel, dropdown

sections

  - Menus, header, footer, sidebar, forms

pages

  - Page-specific styles

utils

  - Mixins, helpers

## Build

A basic example of using Sass with compile, minify and watch tasks: [Sass Example](https://github.com/eliot-akira/sass-example)

An example using Gulp build system: [Boots](https://github.com/eliot-akira/boots)

## References

[Sass Style Guide](https://css-tricks.com/sass-style-guide/)

[Sass Guidelines](http://sass-guidelin.es)

- [Syntax & Formatting](http://sass-guidelin.es/#syntax--formatting)

[The Sass Way](http://thesassway.com/)

- [How to structure a Sass project](http://thesassway.com/beginner/how-to-structure-a-sass-project)

- [Using Object-Oriented CSS with Sass](http://thesassway.com/intermediate/using-object-oriented-css-with-sass)

- [Modular CSS naming conventions](http://thesassway.com/advanced/modular-css-naming-conventions)

- [Modular CSS typography](http://thesassway.com/advanced/modular-css-typography)

- [A standard module definition for Sass](http://thesassway.com/intermediate/a-standard-module-definition-for-sass)
