
<!-- README.md is generated from README.Rmd. Please edit that file -->

# invoiceApp <a href='https://github.com/2DegreesInvesting/r2dii.usethis'><img src='https://imgur.com/A5ASZPE.png' align='right' height='43' /></a>

<!-- badges: start -->

[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/invoiceApp)](https://CRAN.R-project.org/package=invoiceApp)
[![R-CMD-check](https://github.com/2DegreesInvesting/invoiceApp/workflows/R-CMD-check/badge.svg)](https://github.com/2DegreesInvesting/invoiceApp/actions)
[![Codecov test
coverage](https://codecov.io/gh/2DegreesInvesting/invoiceApp/branch/master/graph/badge.svg)](https://codecov.io/gh/2DegreesInvesting/invoiceApp?branch=master)
<!-- badges: end -->

The goal of invoiceApp is to helps users find a scenairo interactively.

## Installation

Install the development version of invoiceApp from GitHub with:

``` r
# install.packages("devtools")
devtools::install_github("2DegreesInvesting/invoiceApp")
```

## Example

``` r
if (interactive()) {
  invoiceApp::run_app()
}
```
