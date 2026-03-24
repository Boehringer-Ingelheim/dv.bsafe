
# dv.bsafe statistical computations package

# B-SAFE Shiny Module

## Installation

``` r
install.packages("remotes")
remotes::install_github("https://github.com/Boehringer-Ingelheim/dv.bsafe")
remotes::install_github("https://github.com/Boehringer-Ingelheim/dv.modules.bsafe")
```

## Usage

``` r
library(dv.bsafe)
library(dv..modules.bsafe)


data <- dv..modules.bsafe::test_data

# tbd
```

## Further Information

B-SAFE is an R-Shiny app. The app is an innovate software tool for statistical analysis of adverse event summary data. The app can enhance the descriptive analysis for a current trial with historical information on one or more treatment arms for increased precision. It features a Bayesian Meta-Analytic Predictive (MAP) Prior approach and a robust extension, which incorporates historical information for safety analyses on adverse events into safety analyses for a new trial. The use of historical information has been used for efficacy analyses in the past and now being extended to safety analyses.

[Manual](https://github.com/Boehringer-Ingelheim/dv.modules.bsafe/blob/main/inst/www/manual.pdf)
