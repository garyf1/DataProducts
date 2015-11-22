pitch
========================================================
author: garyf
date: November 22, 2015

Line fitting on the web
========================================================

Fit a line for a pair of numeric vectors on the web!

- Load 2 integer vectors into the text boxes.
- Application converts the text into integer vectors.
- If the lengths match a plot of points and best fit line is presented
- Any errors are listed on the screen for correction

Working (Test) sets
========================================================

Fit a line for a pair of numeric vectors on the web!

- 1,2,3,4,5,6 and 1,2,3,4,5,6
- Application convert the text into integer vectors.
- If the lengths match   a plot of points and best fit line is presented
- Any errors are listed on the screen for correction

Posted text boxes need to be converted to numeric Vectors
========================================================
### HTTP post vars from a textInput come in as a string.

```r
 postVar <- "0,1,2,3,4,5,6"
 inX = unlist(strsplit(postVar,","))
 inX
```

```
[1] "0" "1" "2" "3" "4" "5" "6"
```
### To be useful, the string needs to be converted to numeric vectors

Sample plot
========================================================

![plot of chunk unnamed-chunk-2](pitch-figure/unnamed-chunk-2-1.png) 
