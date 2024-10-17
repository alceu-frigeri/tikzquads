tikzquads
==========

This package defines a few extra shapes (single / dual port boxes) designed to be used together with
the CircuiTikZ package.


For more details,  see the (some) documentation,

[tikzquads.pdf](http://mirrors.ctan.org/graphics/pgf/contrib/tikzdotncross/doc/tikzquads.pdf)

--------------

## Requirements
* none besides a fairly recent LaTeX distribution as recent as 2022/06/01
(with the new in kernel *\ProcessKeyOptions* and *\NewDocumentCommand*)

and pgf/TikZ or CircuiTikZ

## Installation
The stable version is available at [CTAN](https://ctan.org/pkg/tikzquads).

## Usage
### Stable version
Just place
```latex
  \usepackage{tikzquads}
```

in the preamble and compile away.


Be aware that options might change between versions, so you have to check them manually.


## More Information and documentation
More Information can be found in the documentation; you can find a  "bleeding edge" version
at [the github page](http://github.com/alceu-frigeri/tikzquads)

## Contacting Author

For bug reports and enhancement suggestions, the preferred way is to use
[the project's issue page](https://github.com/alceu-frigeri/tikzquads/issues).
Please be ready to provide an example code showing the bug, if any.

Please do not use the issue page for generic help on how to use the package.

* git: https://github.com/alceu-frigeri/tikzquads

-------------
Copyright 2024-present by Alceu Frigeri

 This work may be distributed and/or modified under the
 conditions of

 * The [LaTeX Project Public License](http://www.latex-project.org/lppl.txt), version 1.3c (or later), and/or
 * The [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html), version 3 (or later)

This work has the LPPL maintenance status *maintained*.

The Current Maintainer of this work is Alceu Frigeri

-------------
## This work consists of the files

* tikzquads.sty
    - The Package itself

* README.md (this file)
    - quick introduction

* tikzquads.tex
    - package documentation

* tikzquads.pdf
    - documentation in PDF format

-------------

## Changelog

* Version 1.1 (this)
    - Added a 'raw sources' key (see manual)
    - a few typos in the documentation

* Version 1.0
    - Initial release by CTAN
