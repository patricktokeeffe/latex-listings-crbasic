CRBasic syntax highlighting for LaTeX `listings` package
========================================================

This package implements partial support for formatting CRBasic source code
following the conventions of the CRBasic Editor using the `listings` LaTeX
package.

## To use

1.  Copy both files (`lstlang0.sty` and `lstlocal.cfg`) into the same
    directory as the source LaTex (or Lyx) file.
2.  Enable the `listings` package and specify in your code listing options:
        "language={[CR]Basic}"


## Related settings

The author frequently sets the following settings in the document preamble
(well, the Document Settings > Listings pane in Lyx):

    breakatwhitespace=true
    breaklines=true
    frame=single
    numbers=left
    numberstyle={\footnotesize}
    showlines=true


## Known differences

At present, the syntax highlighting provided only approximates that provided
by CRBasic Editor. Some known differences (non-exhaustive):

- Variable & constant names are not italicized or colorized
- Not all keywords are recognized
- Some odd highlighting may occur inside comments

## License

This project may be submitted as a contribution to the LaTeX `listings` package
in the future. To ensure a seamless transition, this software is licensed under
the [LaTeX Project Public License 1.3c or later](http://www.latex-project.org/lppl.txt).

## Disclaimer

This project is not affiliated with, supported by, or endorsed by Campbell
Scientific, Inc., the makers of CRBasic.

