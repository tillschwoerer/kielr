
<!-- README.md is generated from README.Rmd. Please edit that file -->

# kielr

<!-- badges: start -->
<!-- badges: end -->

The goal of the package kielr is to provide quizzes accompanying the
courses of the [Data Science Master
Program](https://www.fh-kiel.de/fachbereiche/data-science-interdisziplinaerer-studiengang/)
at [University of Applied Science Kiel](https://www.fh-kiel.de/).

## Installation

You can install the development version of kielr from
[Github](https://github.com/tillschwoerer/kielr) with:

``` r
devtools::install_github("tillschwoerer/kielr", ref = "main")
```

You also need to install the package **learnr** with:

``` r
install.packages('learnr')
```

## Example

To check which tutorials are available run

``` r
learnr::available_tutorials("kielr")
```

To run a specific tutorial run, e.g.

``` r
learnr::run_tutorial("programming1", "kielr")
```
