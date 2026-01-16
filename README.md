# My Personal Website
A lightweight peronsal website that leverages my resume in markdown format to also provide it in HTML and PDF


# exporting
```
pandoc resume.md -o resume.pdf -V geometry:margin=0.4in -V mainfont="Helvetica" -V pagestyle=empty --pdf-engine=xelatex
```