
# Demo

<!-- badges: start -->
[![R-CMD-check](https://github.com/bryandmartin/Demo/workflows/R-CMD-check/badge.svg)](https://github.com/bryandmartin/Demo/actions)
[![codecov](https://codecov.io/gh/bryandmartin/Demo/branch/master/graph/badge.svg?token=bArJfY6BE0)](https://codecov.io/gh/bryandmartin/Demo)
<!-- badges: end -->

The goal of Demo is to ...


## Installation

You can install the package through GitHub using:

``` r
devtools::install_github("bryandmartin/Demo")
```

To view the vignette:

``` r
devtools::install_github("bryandmartin/Demo", build_vignette = TRUE, build_opts = c())
library(Demo)
# Use this to view the vignette in the Demo HTML help
help(package = "Demo", help_type = "html")
# Use this to view the vignette as an isolated HTML file
utils::browseVignettes(package = "Demo")
```


