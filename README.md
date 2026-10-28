# LaTeX manuscript template
This repository contains simple LaTeX templates for scientific manuscripts. The templates are journal-independent and can be used for preparing research papers.

## Main features
- Support for ORCID identifiers with clickable icons next to author names.
- The [`elsarticle-num'](https://www.elsevier.com/researcher/author/policies-and-guidelines/latex-instructions) bibliography style, which provides numbered references and includes article titles and DOIs when available.
- Support for hyperlinks in the bibliography, including clickable DOIs, URLs, and article titles where supported.
- A simple and customizable manuscript structure, including the title, author information, abstract, keywords, main sections, and references.

## Bibliography
The BibTeX bibliography files are maintained in a separate repository: [bibliography](https://github.com/romanik-icmp/bibliography).

The manuscript template uses `articles.bib` and `books.bib`. To make these files accessible to LaTeX, they can be placed:
1. In the same directory as the manuscript `.tex` file.
2. In a directory recognized by the LaTeX installation. For example, in TeX Live 2025 on Windows, the files can be placed in `%USERPROFILE%\texmf\bibtex\bib\`.

The second option allows the same bibliography files to be used across multiple manuscripts without copying them into each project directory.

The location of the personal TeX directory (`TEXMFHOME`) can be determined using: ```kpsewhich -var-value=TEXMFHOME```
