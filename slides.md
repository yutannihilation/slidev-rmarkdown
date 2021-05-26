---
title: test
output:
  md_document:
    variant: "markdown_github"
    preserve_yaml: true

# try also 'default' to start simple
theme: seriph
background: https://raw.githubusercontent.com/yutannihilation/wgpu-practice/4ffc4ff4cba80ac4bfefbba5972985f51c5254a3/sphere/out.gif
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)

# TODO: PDFをダウンロードできるようにする
# download: true
---

# R Markdown

------------------------------------------------------------------------

# Code

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

------------------------------------------------------------------------

# Including Plots

You can also embed plots, for example:

![](/slides_files/figure-markdown_github/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
