# Dynamic documents with R Markdown
These slides summarize the basics of dynamic documents with R Markdown. For a more full discussion, see ... . Also, see below for several helpful links.

# Exercises 
These exercises contain some sample data from a phonetics study and a typological study. The exercises purposely use rather simple r code. The goal of the exercises is for you to feel comfortable using R Markdown and dynamic documents with `knitr`.

Intead of cloning the repo, I recommend downloading the repo and moving the following files and folders from "rstudio\_dynamic\_documents" folder: 

- besemah\_stress.Rmd
- caus\_appl\_syncretism.Rmd
- bib/
- data/ 

You need to install the following packages: 

`install.packages("tidyverse", "knitr", "kableExtra", "leaflet", "wesanderson")`


<center>
### You can rely on  <br/> [this very handy cheatsheet for R Markdown](https://www.rstudio.com/wp-content/uploads/2016/03/rmarkdown-cheatsheet-2.0.pdf) <br/> *and* <br/> [this handy reference guide](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf).
</center>

*If you'd like a more information to reference have a look at [The Definitive Guide to R Markdown](https://bookdown.org/yihui/rmarkdown/)

*If you're feeling a bit confused or intimadated by all of this, feel free to take some time to look over [this very gentle introduction to R Markdown](https://rmarkdown.rstudio.com/lesson-1.html) *or* [this other short introduction](https://kbroman.org/knitr_knutshell/pages/Rmarkdown.html)


## [Exercise 1: Besemah Stress](phonetics_paper.Rmd)
This is a very basic example of a dynamic document. First, use the `knit` command to compile the document. Then, read through the document and look out for commented sections in between \<!-- and -->. For each of these, I list different tasks to complete throughout the document. I'll be walking around to help you complete these tasks. 


## [Exercise 2: Typology of causatives and applicatives](typology_paper.Rmd)
This is a very basic example of a slides using `knitr` and R Markdown. Again, first use the `knit` command to compile the document. Then, read through the document and look out for commented sections in between \<!-- and -->. For each of these, I list different tasks to complete throughout the document. I'll be walking around to help you complete these tasks.

## Exercise 3: Slides in xaringan
Another package worth looking into is [xaringan](https://github.com/yihui/xaringan). It is based upon reveal.js. 

- Install it by running `install.packages(xaringan)`. 
- Click File... > New File > R Markdown...
- Click From template in the left pane 
- Select ninja presentation and then OK.
- The template file explains all of the formatting styles in xaringan. Try it out, and even try to repoduce the slides from Exercise 2 in xaringan. 

## Exercise 4: Experimenting on your own
If you have additional time, you can *either* create slides from the document in **Exercise 1** *or* create a document from the slides in **Exercise 2**. I provide a number of links at the end of exercise 2 for you to get some ideas of how you can do even more with dynamic documents.