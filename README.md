
# Demo

<!-- badges: start -->
[![R-CMD-check](https://github.com/bryandmartin/Demo/workflows/R-CMD-check/badge.svg)](https://github.com/bryandmartin/Demo/actions)
[![codecov](https://codecov.io/gh/bryandmartin/Demo/branch/master/graph/badge.svg?token=XQoAaseg02)](https://codecov.io/gh/bryandmartin/Demo)
<!-- badges: end -->

The goal of Demo is to demonstrate how to build a package.

## Installation

You can install the released version of Demo from GitHub using:

``` r
devtools::install_github("bryandmartin/Demo")
```

To view vignettes, run the following code:

``` r
devtools::install_github("bryandmartin/Demo", build_vignette = TRUE, build_opts = c())
library(Demo)
# Use this to view the vignette in the Demo HTML help
help(package = "Demo", help_type = "html")
# Use this to view the vignette as an isolated HTML file
utils::browseVignettes(package = "Demo")
```

