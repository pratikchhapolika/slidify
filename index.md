---
title       : Slidify 
subtitle    : Data Prsentation
author      : Pratik Chhapolika
job         : Coursera Project
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github: 
            user: pratikchhapolika 
            repo: slidify
---
## Slide 2

```r
 require(ggplot2)
 qplot(wt, mpg, data = mtcars)
```

<img src="figure/simple-plot-1.png" title="plot of chunk simple-plot" alt="plot of chunk simple-plot" style="display: block; margin: auto;" />

---

# Storm Database Explorer


```
## Warning: package 'data.table' was built under R version 3.3.1
```

```
## Warning: package 'reshape2' was built under R version 3.3.1
```

```
## 
## Attaching package: 'reshape2'
```

```
## The following objects are masked from 'package:data.table':
## 
##     dcast, melt
```

---

## Between 1950 and 2011 severe weather events caused at least

 - 14 834 deaths
 - 139 445 injuries
 - $358 billion worth of damage
 

---

## ... and it can generate cool plots


<iframe src=' figure/nvd3plot2-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- populationImpact ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>
 
 




