[![R-CMD-check](https://github.com/taiyun/corrplot/workflows/R-CMD-check/badge.svg)](https://github.com/taiyun/corrplot/actions)
[![Build Status](https://travis-ci.org/taiyun/corrplot.svg?branch=master)](https://travis-ci.org/taiyun/corrplot)
[![codecov.io](https://codecov.io/github/taiyun/corrplot/coverage.svg?branch=master)](https://codecov.io/github/taiyun/corrplot?branch=master)
[![CRAN Status](http://www.r-pkg.org/badges/version/corrplot)](http://cran.r-project.org/package=corrplot)
[![CRAN Downloads](http://cranlogs.r-pkg.org/badges/corrplot)](http://www.r-pkg.org/pkg/corrplot)
[![Support badge](https://img.shields.io/badge/stackoverflow-corrplot-yellowgreen.svg)](http://stackoverflow.com/questions/tagged/r-corrplot)

## Summary

R package **corrplot** focuses on reordering and visualizing correlation matrix. 
It can also draw clusters, p-values and confidence intervals on correlation matrix plot. 
corrplot is very easy to use and good at plotting details, including visualization method, 
layout, color choosing and assigning, color-legend, text labels, cluster rectangles, 
p-values, confidence intervals, NA values, math labels etc.

For examples, see its
[online vignette](http://cloud.r-project.org/web/packages/corrplot/vignettes/corrplot-intro.html).

This package is licensed under the MIT license, and available on CRAN:
<http://cran.r-project.org/package=corrplot>.



## Basic example

```r
library(corrplot)
M = cor(mtcars)
corrplot(M, order = 'hclust', addrect = 2)
```
![Basic example](https://raw.githubusercontent.com/taiyun/corrplot/master/vignettes/webimg/rectangles-1.png)

## Download and Install

To download the release version of the package on CRAN, type the following at the R command line:

```r
install.packages('corrplot')
```

To download the development version of the package, type the following at the R command line:

```r
devtools::install_github('taiyun/corrplot', build_vignettes = TRUE)
```

## How to cite

To cite `corrplot` properly, call the R built-in command
`citation('corrplot')` as follows:

```r
citation('corrplot')
```

## Reporting bugs and other issues

If you encounter a clear bug, please file a minimal reproducible example on 
[github](https://github.com/taiyun/corrplot/issues).

