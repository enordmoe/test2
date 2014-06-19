---
title       : This is a Test Deck
subtitle    : June 19, 2014
author      : Eric Nordmoe
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Histogram of Normal Random Variable

Create a plot in ggplot2:

```r
require(ggplot2)
x=rnorm(1000)
hist(x)
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1.png) 

---

## Unordered Lists

* Main point 1
* Main point 2
  + Sub point 2a
  + Sub point 2b
  
One sample $t$ confidence interval for mean:
$$
\bar X \pm t^* \frac{s}{\sqrt{n}}
$$
  






