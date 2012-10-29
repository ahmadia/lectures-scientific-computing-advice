## Scientific Computing for Numerical Mathematicians Lecture

There are a plethora of techniques, tools, languages, and platforms available to help you scientifically compute. 
It is likely that you will only be able to afford a limited amount of time learning a subset of them. The purpose 
of this lecture is to help orient you on the path to writing software as part of your research by: 

* introducing the important tools and paradigms of software construction
* relating them to your role as a scientist, and
* making specific recommendations for 
    + selecting tools that you should be using 
    + and practices that you should be following

* three themes I focus on are:
    + **reducing complexity**
    + **automating your workflow**
    + **encouraging experimentation**

## About this Repository

This repository contains only the source text for building the presentation, `slides.md`, but you will find the file 
to be perfectly readable.  The slides are written in pandoc Markdown (built with syntax highlighting enabled), and 
are converted to html with the following command: 

    pandoc --slide-level 2 -t slidy  --standalone --self-contained  -s slides.md -o slides.html

Thanks to Ingrid von Glehn for finding two errors in the slides.