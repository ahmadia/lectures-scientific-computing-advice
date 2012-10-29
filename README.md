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

## Reuse

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.en_US">
<img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/3.0/88x31.png" />
</a><br />
<span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/InteractiveResource" 
property="dct:title" rel="dct:type">Fundaments of Computational Software Engineering</span> 
by <a xmlns:cc="http://creativecommons.org/ns#" href="http://aron.ahmadia.net" 
property="cc:attributionName" rel="cc:attributionURL">Aron Ahmadia</a> is licensed under a <a rel="license" 
href="http://creativecommons.org/licenses/by/3.0/deed.en_US">Creative Commons Attribution 3.0 Unported License</a>.

## About this Repository

This repository contains only the source text for building the presentation, `slides.md`, but you will find the file 
to be perfectly readable.  The slides are written in 
[pandoc Markdown](http://johnmacfarlane.net/pandoc/demo/example9/pandocs-markdown.html), and 
are converted to html with the following call to a [pandoc](http://johnmacfarlane.net/pandoc/) >=1.9 
built with syntax-highlighting: 

    pandoc --slide-level 2 -t slidy  --standalone --self-contained  -s slides.md -o slides.html

Thanks to Ingrid von Glehn for finding two errors in the slides.