---
title: "Module 3 HTML Document"
author: "your name"
date: "7/6/2021"
output: 
  html_document: 
    keep_md: true
    fig_width: 6
    fig_height: 6
    toc: yes
    toc_float: true
    code_folding: hide
---


# Module 3 - HTML document

## R Markdown {#nextsteps .emphasized}

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

### Preview and plot of ```cars``` Dataset


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

```r
plot(cars)
```

![](index_files/figure-html/cars-1.png)<!-- -->

## Including Plots

You can also embed plots, for example:

### Plot of the ```pressure``` Dataset

![](index_files/figure-html/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

## Shopping list

1. Breakfast
    a. food
        i. eggs
        ii. toast
        iii. bacon
    b. drink
        i. apple juice
2. Lunch
    a. taco
3. Dinner
    a. baked chicken
    b. broccoli
    c. rice


## Simple equation using LaTex

$$ Y = \beta_0 + \beta_1x + \beta_1*x - \gamma_2w $$
