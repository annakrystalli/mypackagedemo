
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypackage

<!-- badges: start -->

[![R-CMD-check](https://github.com/annakrystalli/mypackagedemo/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/annakrystalli/mypackagedemo/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of mypackage is to print a personalised greeting from me!

## Installation

You can install the development version of mypackage from GitHub with:

``` r
# install.packages("remotes")
remotes::install_github("annakrystalli/mypackagedemo")
```

## Example

This is a basic example which shows you how to print a generic greeting:

``` r
library(mypackagedemo)
## basic example code
hello()
```

    ## 
    ##  ------------------------ 
    ## < Hello world from Anna! >
    ##  ------------------------ 
    ##         \
    ##          \
    ## 
    ##            _,
    ##       -==<' `
    ##           ) /
    ##          / (_.
    ##         |  ,-,`\
    ##          \\   \ \
    ##           `\,  \ \
    ##            ||\  \`|,
    ##  jgs      _|| `=`-'
    ##          ~~`~`

This is a basic example which shows you how to print a personalised
greeting:

``` r
hello(name = "Lucy Elen")
```

    ## 
    ##  ---------------------------- 
    ## < Hello Lucy Elen from Anna! >
    ##  ---------------------------- 
    ##       \
    ##        \
    ## 
    ##         ^__^ 
    ##         (oo)\ ________ 
    ##         (__)\         )\ /\ 
    ##              ||------w|
    ##              ||      ||
