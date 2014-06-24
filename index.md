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
Example for a woman of 193 cm

```r
height <- 193; # height is in cm
toInch = height / 2.54;  
feet5 <- 12 * 5;
if( toInch > feet5 ){
      toInch <- toInch - feet5;
} else {
      toInch <- 0;
}
idealWeight <- 49 + 1.7 * toInch
idealWeight
```

[1] 76.17


---

## Slide 4

Stay healthy!!

Stay in shape!!

---

## Slide 5

Thanks Prof. Caffo
