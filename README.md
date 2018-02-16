The gambin R package
====================

[![Build Status](https://travis-ci.org/txm676/gambin.svg?branch=master)](https://travis-ci.org/txm676/gambin) [![Downloads](http://cranlogs.r-pkg.org/badges/gambin?color=brightgreen)](http://cran.rstudio.com/package=gambin) [![CRAN](http://www.r-pkg.org/badges/version/gambin)](http://cran.rstudio.com/package=gambin) [![codecov.io](https://codecov.io/github/txm676/gambin/coverage.svg?branch=master)](https://codecov.io/github/txm676/gambin?branch=master)

[![Downloads](http://cranlogs.r-pkg.org/badges/poweRlaw?color=brightgreen)](http://cran.rstudio.com/package=poweRlaw) [![CRAN](http://www.r-pkg.org/badges/version/poweRlaw)](http://cran.rstudio.com/package=poweRlaw)

This package fits the `gambin` distribution to species-abundance distributions from ecological data. 'gambin' is short for 'gamma-binomial'. The main functions are `fit_abundances`, which estimates the `alpha` parameter of the gambin distribution using maximum likelihood, and `mult_abundances` which estimates `alpha` for multiple sites / samples after standardising for the number of individuals. Recent functions are also provided to generate the gambin distribution and for calculating likelihood statistics. The package now provides functionality to fit multimodal gambin distributions.

The package is currently on CRAN and can be installed via

``` r
install.packages("gambin")
```

Alternatively, you can install the developmental version via

``` r
devtools::install_github("txm676/gambin")
```
