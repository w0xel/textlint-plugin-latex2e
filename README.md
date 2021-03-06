# Textlint Plugin LaTeX2ε
[![npm](https://img.shields.io/npm/v/textlint-plugin-latex2e.svg)](https://www.npmjs.com/package/textlint-plugin-latex2e)
[![actions](https://github.com/fgborges/textlint-plugin-latex2e/workflows/Node%20CI/badge.svg)](https://github.com/fgborges/textlint-plugins-latex2e/actions)

This plugin contains rough LaTeX parser which doesn't cover all syntax, but it's enough.

We welcome your contribution for adding new syntax! Thanks.

## Installation

```
$ npm install textlint-plugin-latex2e
```

And add to `.textlintrc`

```
   plugins: ["latex2e"]
```

## Known Issue

This kind of syntax cannot be interpreted correctly.

```latex
\newenvironment{A}
{\begin{B}}
{\end{B}}
```

To avoid this issue, you can write them out of the file with `\input` command.

## Copyright

Copyright (C) 2018 Fernando Garcia Borges ALL Rights Reserved.

## License

This software is licensed under the GPLv3 or later.
