
<!-- README.md is generated from README.Rmd. Please edit that file -->

# <img src="https://i.imgur.com/3jITMq8.png" align="right" height=40 /> Access raw or lightly-prepared data

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
<!-- badges: end -->

The goal of the r2dii.dataraw package is to access raw or
lightly-prepared data. It allows you to access “live” data from 2dii’s
dropbox folder and to take a snapshot of it.

## Installation

To minimize installation errors, ensure your R environment is as
follows:

  - R version is recent.
  - All packages are updated (run `update.packages()`; maybe use `ask =
    FALSE`).
  - No other R session is running.
  - Current R session is clean (click *Session \> Restart R*).

<!-- end list -->

``` r
# install.packages("devtools")

# To install from a private repo, see ?usethis::browse_github_token()
devtools::install_github("2DegreesInvesting/r2dii.dataraw", auth_token = "abc")
```

## Example

[Go to examples](https://2degreesinvesting.github.io/r2dii/#examples)
