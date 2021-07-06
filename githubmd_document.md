# Module 3 - HTML document

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

### Preview and plot of `cars` Dataset

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

``` r
plot(cars)
```

![](githubmd_document_files/figure-markdown_github/cars-1.png)

## Including Plots

You can also embed plots, for example:

### Plot of the `pressure` Dataset

![](githubmd_document_files/figure-markdown_github/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

## Shopping list

1.  Breakfast
    1.  food
        1.  eggs
        2.  toast
        3.  bacon
    2.  drink
        1.  apple juice
2.  Lunch
    1.  taco
3.  Dinner
    1.  baked chicken
    2.  broccoli
    3.  rice

## Simple equation using LaTex

*Y* = *β*<sub>0</sub> + *β*<sub>1</sub>*x* + *β*<sub>1</sub> \* *x* − *γ*<sub>2</sub>*w*
