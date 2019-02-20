
<!-- README.md is generated from README.Rmd. Please edit that file -->

# hardhat

<!-- badges: start -->

[![Travis build
status](https://travis-ci.org/DavisVaughan/hardhat.svg?branch=master)](https://travis-ci.org/DavisVaughan/hardhat)
[![Codecov test
coverage](https://codecov.io/gh/DavisVaughan/hardhat/branch/master/graph/badge.svg)](https://codecov.io/gh/DavisVaughan/hardhat?branch=master)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/hardhat)](https://cran.r-project.org/package=hardhat)
<!-- badges: end -->

## Introduction

hardhat is designed to ease the creation of new modeling packages, while
simultaneously promoting good R modeling package standards as laid out
by the set of opinionated [Conventions for R Modeling
Packages](https://tidymodels.github.io/model-implementation-principles/).

The idea is to take as much of the burden around creating a good
interface off the developer as possible, and instead let them focus on
writing the core implementation of the model. This benefits not only the
developer, but also the user of the modeling package, as the
standardization allows users to build a set of “expectations” around
what any modeling function should return, and how they should interact
with it.

``` r
library(hardhat)
```

## Installation

You can install the released version of hardhat from
[CRAN](https://CRAN.R-project.org) with:

``` r
# no you cannot
install.packages("hardhat")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("DavisVaughan/hardhat")
```

## Example

hardhat will mainly be useful to developers, and it allows you to
develop new modeling packages that implement formula, data frame,
matrix, and recipes interfaces with ease.

There are a number of useful functions in hardhat, but two of the most
important ones are `mold()` and `forge()`.
