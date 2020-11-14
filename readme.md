## Overview

Work-in-progress syntax for the Rebol/Red programming languages in Sublime Text.

Current features:

* Support for all Rebol literals.
* Support for `ident:` declarations. Indexing/goto for file-level declarations.
* Support for `func` and `function`. Appropriate detection of function declarations, parameters, and locals.
* Support for `<tags>`.
* Support for arbitrary `types!`.
* Correct "word boundaries" setting, making it easier to skip words, use goto, etc.

Current limitations / TODO:

* No syntax tests.
* No special support for built-in functions, operators, types, etc.
* No special support for function refinements.
* Incomplete support for `comment`.
* No support for hex integers.
* No support for Red/System compiler directives such as `#define`.
* Lack of indentation rules.
* Probably a lot of things I don't know about.

## Installation

Clone the repo and symlink it to your Sublime packages directory. Example for MacOS:

```sh
git clone https://github.com/mitranim/sublime-rebol.git
cd sublime-rebol
ln -sf "$(pwd)" "$HOME/Library/Application Support/Sublime Text 3/Packages/"
```

To find the packages directory on your system, use Sublime Text menu → Preferences → Browse Packages.

## License

https://unlicense.org
