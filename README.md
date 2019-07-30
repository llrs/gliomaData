
<!-- README.md is generated from README.Rmd. Please edit that file -->

# gliomaData

<!-- badges: start -->

[![Travis build
status](https://travis-ci.org/llrs/gliomaData.svg?branch=master)](https://travis-ci.org/llrs/gliomaData)
<!-- badges: end -->

The goal of gliomaData is to provide data for RGCCA vignettes.

## Installation

You can install the released version of gliomaData from
[GitGhub](https://github.com/llrs/gliomaData) with:

``` r
devtools::install("llrs/gliomaData")
```

The original version of the data can be found
[here](http://biodev.cea.fr/sgcca/).

## Examples

Some data provided by the package:

``` r
library(gliomaData)
data(clinic)
clinic[1:5, 1:10]
#>       ID CGH CGH_barcode GE GE_barcode CGH.GE CGH_only GE_only sexe age_j
#> 484N P01   1   26606_1_1  1  12313_1_2      1        0       0    F    NA
#> 541N P02   1   26622_1_1  1  12313_1_3      1        0       0    F    NA
#> ADOM P03   1   28068_1_1  1  11955_1_1      1        0       0    F  2885
#> BAUK P04   1   14175_1_3  1  27014_1_4      1        0       0    M    NA
#> BERG P05   1   14175_1_4  1  27014_1_3      1        0       0    M    NA
```
