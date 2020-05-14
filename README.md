
<!-- README.md is generated from README.Rmd. Please edit that file -->

# testgitaction

<!-- badges: start -->

[![R build
status](https://github.com/chriszheng2016/testgitaction/workflows/R-CMD-check/badge.svg)](https://github.com/chriszheng2016/testgitaction/actions)
[![Codecov test
coverage](https://codecov.io/gh/chriszheng2016/testgitaction/branch/master/graph/badge.svg)](https://codecov.io/gh/chriszheng2016/testgitaction?branch=master)
![test-coverage](https://github.com/chriszheng2016/testgitaction/workflows/test-coverage/badge.svg)
[![pkgdown](https://github.com/chriszheng2016/testgitaction/workflows/pkgdown/badge.svg)](https://chriszheng2016.github.io/testgitaction/)
<!-- badges: end -->

**NOTE: This is a toy package created for expository purposes, for the
second edition of [R Packages](https://r-pkgs.org). It is not meant to
actually be useful. If you want a package for factor handling, please
see [forcats](https://forcats.tidyverse.org).**

# foofactors

Factors are a very useful type of variable in R, but they can also be
very aggravating. This package provides some helper functions for the
care and feeding of factors.

## Installation

You can install the released version of testgitaction from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("testgitaction")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("chriszheng2016/testgitaction")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
# comment to make render readme.md since testgitaction
# doesn't exit
#library(testgitaction)

## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub\!
