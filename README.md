# My Personal Website
A lightweight peronsal website that leverages my resume in markdown format to also provide it in HTML and PDF


# exporting
```
pandoc resume.md -o resume.pdf -V geometry:margin=1in -V mainfont="Helvetica" --pdf-engine=xelatex
```