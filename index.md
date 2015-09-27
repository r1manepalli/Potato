---
title       : Predict Potato Adj Close Price
subtitle    : This Presentation contains detail of the Data product to predict future stock price
author      : r1
job         : Eating Potatos
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit: slidify::knit2slides
---

## Introduction of the Data Product

The following data product had functionality to accept
the High price and the Close price of a given day for future until 2025
and predict the adjusted close stock price of the Potato Company.

This fictional Potato company uses a six months worths data to train from april 2015 thru Sep 2015
before evaluating the input parameters and predict the future.

--- .class #id1

## Steps to create the product

1. A shinyUI program was written with sidebar panel and Main Panel
2. A server program was written that consumed history data of Potato Company
3. A GLM predict fuction was executed to predict the adjusted close price.

--- .class #id1

## Basic data input for the Predictive data product


```r
Potato <- c(20150925, 20, 30)
 
head(Potato)
```

```
## [1] 20150925       20       30
```

--- .class #id3

## Conclusion

We can create many good Data predictive products in the investment market



--- .class #id4
