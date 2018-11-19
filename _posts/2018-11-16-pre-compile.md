---
layout: post
title:  "Pre-compiling the CSS?"
date:   2018-11-16 16:55:00 +0100
---

Do you know the feeling of infinitely using "copy/paste" when creating CSS? How about the time flying by when trying to find all occurrences in the CSS when the boss tells you "please, can you change that feature"? Apparently developers got tired of the limitations of CCS, and some of them created programs known as *CSS preprocessors*.

A CSS preprocessor uses its own syntax and generates the CSS and will work as an extension of the regular CSS. Originally, the idea was to solve the following problems ([see reference](https://rawgit.com/1dv022/syllabus/master/lectures/01/index.html#/3)): 

* Less css to maintain
* DRY css
* Make calculations in your css
* Better organized css
  * Nesting
  * Separate in files
  * Use mixins
* Use variables!

However, as the regular CSS evolves and adopts more and more of the requested tools, using CSS preprocessors might no longer be relevant. One thing to bear in mind is that once a site is built with a certain CSS preprocessor, it might be difficult to change back to the regular CSS later. The maintenance team gets stuck to one more tool. Furthermore, using a CSS preprocessor might lead to the following disadvantages ([see reference](https://rawgit.com/1dv022/syllabus/master/lectures/01/index.html#/6) and further reading at [adamsilver.io](https://adamsilver.io/articles/the-disadvantages-of-css-preprocessors/)):

* Harder to debug your code
  * Line numbers in browser !== line numbers in source
* Greater complexity
  * More tools
  * More setup
* Building times increase
* Save generated files in source control?

The CSS of this site has been developed using [Sass](https://sass-lang.com/). Other CSS preprocessors are [{less}](http://lesscss.org/) and [stylus](http://stylus-lang.com/). Of the advantages listed above, the _use of variables_ was the one I benefitted the most in this project, making it possible to easily change and evaluate different colors schemes.
