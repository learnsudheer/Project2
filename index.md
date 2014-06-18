---
title       : Data Products - Course Project
subtitle    : Part II - Reproducible Pitch Presentation
author      : LearnSudheer
job         : IT Analyst
logo        : logo.jpg
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## read me:

There are 5 slides in this deck, please go through all the slides by clicking left/right arrows.

Slide 1: Running R code with 'echo=FALSE'

Slide 2, Running R code with 'echo=TRUE'

Slide 3, Running R code with 'echo=TRUE, result = hide'

Slide 4, code that doesnt evaluate

Slide 5, Sample Scatter Plot


--- .class #id 

## Slide 1, Running R code with 'echo=FALSE'


```
## [1] 55
```

```
## [1] 9.167
```

--- .class #id 

## Slide 2, Running R code with 'echo=TRUE'


```r
sum(1 : 10)
```

```
## [1] 55
```

```r
10*(11)/12
```

```
## [1] 9.167
```

--- .class #id 

## Slide 3, Running R code with 'echo=TRUE, result = hide'



```r
sum(1 : 10)
10*(11)/12
```

--- .class #id 

## Slide 4, code that doesnt evaluate

```
1 + 2 + 3 
```

--- .class #id 

## Slide 5, Sample Scatter Plot


```r
attach(mtcars)
```

```
## The following objects are masked from mtcars (position 3):
## 
##     am, carb, cyl, disp, drat, gear, hp, mpg, qsec, vs, wt
```

```r
plot(wt, mpg, main="Scatterplot Example", 
     xlab="Car Weight ", ylab="Miles Per Gallon ", pch=19)
```

![plot of chunk unnamed-chunk-4](assets/fig/unnamed-chunk-4.png) 

![plot of chunk simple-plot](figure/simple-plot.png) 
