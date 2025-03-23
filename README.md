
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypackage

<!-- badges: start -->
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
    ##                    \
    ##                     \
    ## 
    ## 
    ##                       @@@@@@@@@@@@@@
    ##                    @@@@@@@@@@@@@@@@@@@@@@
    ##                   @@@@@@@@@@@@@@@@@@@@@@@@@
    ##                   @@@@@@@@@@@@@@@@@@@@@@@@@@
    ##                   @@@@@@@@@@@@@@@@@@@@@@@@@@
    ##                  @@@@@@@@@@@@@@@@@@@@@@@@@@@
    ##                  @@@@@@@@@@@@@@@@@@@@@@@@@@@@
    ##                 @@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    ##                 @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    ##                @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    ##  @             @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    ##   @@           @@@@@@@@@@@@@@@@@@     @@@@@@@@@@@@@@@@@@@@@
    ##     @@@@@@@@@@@@@@@@    @@ @@@@         @@  @@@@@@@@@@@@@@@
    ##        @@@@@@@@@@@@@      @@@@          @@@@@@@@@@@@@@@@@@@
    ##           @@@@@@ @@@@@    @@@   @       @@@@@@@@@@ @@@@@@@
    ##               @@     @ @                @@ @@@@@@@@   @@@
    ##                                               @@@@@@@  @
    ##                 @     @@                   @ @@@@@@@@@
    ##                              @               @@@@@@@@ @@
    ##                      @@@@@@@@@@          @  @@@@@
    ##                   @@@@@@@@@@ @@           @@@@@  @
    ##                  @@@@        @@ @          @@@  @
    ##                   @@@           @          @@@
    ##                    @@@@@@@   @@ @          @@@@@
    ##                     @@@@@@@@@@            @@@@
    ##                      @@@@@@ @     @     @@@@@@@@
    ##                   @@ @ @@@@@@@@@ @@@@@@@@@@@@@@@@@
    ##                 @@@  @@@@@   @@@@@@@@@@@@@@@@@@@@@
    ##       @@@@@@  @@@@@   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    ## @@    @@@@  @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ [nosig]
    ## 

This is a basic example which shows you how to print a personalised
greeting:

``` r
hello(name = "Lucy Elen")
```

    ## 
    ##  ---------------------------- 
    ## < Hello Lucy Elen from Anna! >
    ##  ---------------------------- 
    ##          \
    ##           \
    ## 
    ##             |\___/|
    ##           ==) ^Y^ (==
    ##             \  ^  /
    ##              )=*=(
    ##             /     \
    ##             |     |
    ##            /| | | |\
    ##            \| | |_|/\
    ##       jgs  //_// ___/
    ##                \_)
    ## 
