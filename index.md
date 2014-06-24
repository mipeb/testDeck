---
title       : Ideal Weight Calculator
subtitle    : 
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## Ideal Weight

1. Calc ideal weight
2. Stay healthy and in shape
3. Thanks Prof. Caffo


--- .class #id 

## Slide 3 - Calc ideal weight


```r
  idealWeight <- 1;
  gender <- "woman" # or "man"
  height <- 193;

  toInch = height / 2.54;  # height is in cm
  feet5 <- 12 * 5;

  if( toInch > feet5 ){
      toInch <- toInch - feet5;
  } else {
      toInch <- 0;
  }
  
  if( gender == "man" ){
    idealWeight <- 52 + 1.9 * toInch;
  } else { # gender = "woman"
    idealWeight <- 49 + 1.7 * toInch;
  }
  idealWeight # in Kg
```

```
## [1] 76.17
```


---

## Slide 4

Stay healthy!!

Stay in shape!!

---

## Slide 5

Thanks Prof. Caffo
