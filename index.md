---
title       : This is a Test Deck
subtitle    : June 19, 2014
author      : Eric Nordmoe
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
github:
  user: enordmoe
  repo: test2

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
x = rnorm(1000)
qplot(x)
```

```
## stat_bin: binwidth defaulted to range/30. Use 'binwidth = x' to adjust this.
```

![plot of chunk chunk1](assets/fig/chunk1.png) 


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
  

---

## Include a Local images

Here is my picture on a slide:

![image from redmond barry building unimelb](http://i.imgur.com/RVNmr.jpg)

 Here's another picture:
![local image]('/Users/enordmoe/Documents/MySite/ephoto.jpg')





