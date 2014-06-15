---
title       : It All Averages Out . . .
subtitle    : (. . . A Shiny Application)
author      : created by hotnow
job         : 
framework   : io2012               # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js         # {highlight.js, prettify, highlight}
hitheme     : tomorrow             # tomorrow
widgets     : [bootstrap, quiz]    # {mathjax, quiz, bootstrap}
mode        : selfcontained        # {standalone, draft}
---

## Definitions

Given two numbers 'x' and 'y', there are at least three different ways to compute their mean.

The means we can explore in this application are as follows:

- Arithmetic mean: (x+y) / 2
- Geometric mean: sqrt(x*y)
- Harmonic mean: 2 / [1/x + 1/y]


--- .class #id 

## For example...

Suppose x = 10 and y = 40, then we have the following:

```r
x <- 10
y <- 40
paste("Arithmetic mean = ", (x + y)/2)
```

```
## [1] "Arithmetic mean =  25"
```

```r
paste("Geometric mean = ", sqrt(x * y))
```

```
## [1] "Geometric mean =  20"
```

```r
paste("Harmonic mean = ", 2/(1/x + 1/y))
```

```
## [1] "Harmonic mean =  16"
```


--- &radio 

## Which one is smallest?

Of the three types of averages included in the application, which one is always at least as small as the other two?

1. Arithmetic Mean
2. Geometric Mean
3. _Harmonic Mean_

*** .hint 
That's not correct. Please make a different choice.

*** .explanation 
The arithmetic mean is at least as large as the other two, while the harmonic mean is always the smallest or tied for the smallest.


---

## Go check out the app!
..article: 
<br>
<img class = 'centered' src = "libraries/frameworks/io2012/images/averages.png" 
  height = 90%>
</img>


