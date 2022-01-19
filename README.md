
<!-- README.md is generated from README.Rmd. Please edit that file -->

# StatCompLab

<!-- badges: start -->
<!-- badges: end -->

This package collects workshop materials for Statistical Computing
(MATH10093) at the University of Edinburgh 2021/22.

The tutorial documents are browsable online at
<https://finnlindgren.github.io/StatCompLab/>

Contact Finn Lindgren, <finn.lindgren@ed.ac.uk> for information.

The package version number system is
`YearOfStudy`.`StudyWeek`.`MinorUpdate`

## Installation

You can install (and later upgrade) the package from
[GitHub](https://github.com/) with:

``` r
# If devtools isn't installed, first run install.packages("devtools")
devtools::install_github("finnlindgren/StatCompLab", build_vignettes = TRUE)
```

## Example

``` r
library(StatCompLab)
vignette(package = "StatCompLab") # List available vignettes
vignette("Tutorial01", "StatCompLab") # View a specific vignette
library(learnr)
available_tutorials("StatCompLab") # List available tutorials
run_tutorial("Tutorial01", "StatCompLab") # Run a specific tutorial
```
