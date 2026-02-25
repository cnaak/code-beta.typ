# code-beta: Unofficial TLG® Beta Code for Typst

According to the The TLG® Beta Code Manual [1], **Beta Code** is an ASCII-based encoding standard, developed by David W. Packard in the
late 1970s and adopted by TLG® in 1981, for accurately representing polytonic Greek (and archaic languages). It's the de facto standard,
used by Perseus, PHI, Duke Papyri, and Cornell/OSU Epigraphy projects.

Beta Code support in Typst is particularly exciting: beyond ASCII character encoding for polytonic Greek, it includes built-in
typesetting controls for pages, columns, tables, and formatting, enabling, in theory, faithful reproduction of scholarly editions in
Typst without external preprocessing, once all features get implemented.

`code-beta` debuts as a _partial_ implementation of the standard, focusing on the Greek.

## Brief Release Summary

- `0.1.0` - initial release

## Citing

This package can be cited with the following bibliography database entry:

```yml
code-beta-package:
  type: Web
  author: Naaktgeboren, C.
  title:
    value: "code-beta: Unofficial TLG® Beta Code for Typst"
    short: "code-beta: Beta Code for Typst (Unofficial)"
  url: https://github.com/cnaak/blindex.typ
  version: 0.1.0
  date: 2026-02
```

# References

```
[1] Pantelia, M. (Ed.), The TLG® Beta Code Manual, Thesaurus Linguae Graecae, 2016.
    http://www.tlg.uci.edu/encoding/BCM.pdf.

[2] Yannis Haralambous. Guidelines and Suggested Amendments to the Greek Unicode Tables.
    21st International Unicode Conference, Unicode Consortium, May 2002, Dublin, Ireland.
    Paper hal-02112005. https://hal.archives-ouvertes.fr/hal-02112005.

[3] The Unicode Consortium. The Unicode Standard, Version 15.0.0, (Mountain View, CA: The
    Unicode Consortium, 2022. ISBN 978-1-936213-32-0).
    https://www.unicode.org/versions/Unicode15.0.0. Accessed 2023-05-02.
```

