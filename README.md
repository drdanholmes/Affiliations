# Affiliations
RMarkdown Templates for Managing Academic Affiliations for MS-Word and LaTeX

# Background
The repository provides an RMardown templte for MS-Word or PDF output that allows for multiple authors with disparate affiliations. The problem and solution are discussed [here](http://labrtorian.com/2019/08/26/rmarkdown-template-that-manages-academic-affiliations/). The template handles authors, affiliations, emails, cross referencing of figures/tables, references and reference abbrebations.

The output for MS-Word looks like this:

![multiple authors with affiliations](https://raw.githubusercontent.com/drdanholmes/Affiliations/master/Images/goodheader.png "Word Output")

# Requirements

+ RMarkdown and all the associated knitr goodies
+ [bookdown package](https://bookdown.org/)
+ pandoc
+ pandoc-citeproc
+ pandoc-crossref
+ lua
+ [lua scholarly metadata filter](https://github.com/pandoc/lua-filters/tree/master/scholarly-metadata)
+ [lua author info blocks filter](https://github.com/pandoc/lua-filters/tree/master/author-info-blocks)
+ LaTeX and the authblk package if you want PDF output

# Use

Download .Rmd templates and folders, put them in a directory, open either the Word or LaTeX template in knit. All of the necessary filters and files are in the Extras folder.

# Contact

dtholmes@mail.ubc.ca



