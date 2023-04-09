# TEKNOFEST LaTeX Template

This is a LaTeX template that can be used in Overleaf created for the purpose of submitting projects to TEKNOFEST.

You can use this template instead of Word so that you can create much better projects!

## Adding images
1. Add your images to the ./image folder.
2. If you are using turkish babel, make sure to use \shorthandoff{=} before and \shorthandon{=} after the code for adding the image. Examples are available in main.tex

## Adding References
This project is using biblatex with bibtex backend so you can change it if you would like to. 
Use \printbibliography in order to showcase all the citations.
If you have things you have not cited use \nocite{citekey,citekey2}

## Sections
You can add sections as you like. Some of the options are \section, \subsection, \subsubsection, \paragraph etc.

## Adding Figures
If you want to add figures you can use the TikZ package. Here is a link: https://tikz.dev/
