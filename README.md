
<!-- README.md is generated from README.Rmd. Please edit that file -->

# tidymodels <a href='https://tidymodels.tidymodels.org'><img src='tidymodels_hex.png' align="right" height="139" /></a>

<!-- badges: start -->

[![R build
status](https://github.com/tidymodels/tidymodels/workflows/R-CMD-check/badge.svg)](https://github.com/tidymodels/tidymodels)
[![Coverage
status](https://codecov.io/gh/tidymodels/tidymodels/branch/master/graph/badge.svg)](https://codecov.io/github/tidymodels/tidymodels?branch=master)
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/tidymodels)](http://cran.r-project.org/web/packages/tidymodels)
[![R build status](https://github.com/tidymodels/tidymodels/workflows/R-CMD-check/badge.svg)](https://github.com/tidymodels/tidymodels/actions)
[![Codecov test coverage](https://codecov.io/gh/tidymodels/tidymodels/branch/master/graph/badge.svg)](https://codecov.io/gh/tidymodels/tidymodels?branch=master)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/tidymodels)](http://cran.r-project.org/web/packages/tidymodels)
[![Downloads](http://cranlogs.r-pkg.org/badges/tidymodels)](http://cran.rstudio.com/package=tidymodels)
![](https://img.shields.io/badge/lifecycle-experimental-orange.svg)
<!-- badges: end -->

[tidymodels](https://www.tidymodels.org/) is a “metapackage” for
modeling and statistical analysis that shares the underlying design
philosophy, grammar, and data structures of the
[tidyverse](https://www.tidyverse.org/).

It includes a core set of packages that are loaded on startup:


* [`broom`](https://broom.tidymodels.org/) takes the messy output of built-in functions in R, such as `lm`, `nls`, or `t.test`, and turns them into tidy data frames.

* [`dials`](https://dials.tidymodels.org) has tools to create and manage values of tuning parameters.

  - [`ggplot2`](http://ggplot2.tidyverse.org) implements a grammar of
    graphics.

  - [`infer`](http://infer.netlify.app) is a modern approach to
    statistical inference.

  - [`parsnip`](https://parsnip.tidymodels.org) is a tidy, unified
    interface to creating models.

* [`parsnip`](https://parsnip.tidymodels.org) is a tidy, unified interface to creating models. 


  - [`recipes`](https://recipes.tidymodels.org) is a general data
    preprocessor with a modern interface. It can create model matrices
    that incorporate feature engineering, imputation, and other help
    tools.

* [`recipes`](https://recipes.tidymodels.org) is a general data preprocessor with a modern interface. It can create model matrices that incorporate feature engineering, imputation, and other help tools.

* [`rsample`](https://rsample.tidymodels.org) has infrastructure for _resampling_ data so that models can be assessed and empirically validated. 

* [`tibble`](http://tibble.tidyverse.org) has a modern re-imagining of the data frame.
 
* [`tune`](https://tune.tidymodels.org) contains the functions to optimize model hyper-parameters.
 
* [`workflows`](https://workflows.tidymodels.org) has methods to combine pre-processing steps and models into a single object. 

* [`yardstick`](https://yardstick.tidymodels.org) contains tools for evaluating models (e.g. accuracy, RMSE, etc.)


## Installation

You can install the released version of tidymodels from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("tidymodels")
```

Install the development version from GitHub with:

``` r
require("devtools")
install_github("tidymodels/tidymodels")
```

When loading the package, the versions and conflicts are listed:

``` r
library(tidymodels)
#> ── Attaching packages ────────────────────── tidymodels 0.1.0 ──
#> ✓ broom     0.5.6      ✓ recipes   0.1.13
#> ✓ dials     0.0.7      ✓ rsample   0.0.7 
#> ✓ dplyr     1.0.0      ✓ tibble    3.0.1 
#> ✓ ggplot2   3.3.2      ✓ tune      0.1.0 
#> ✓ infer     0.5.2      ✓ workflows 0.1.1 
#> ✓ parsnip   0.1.1      ✓ yardstick 0.0.6 
#> ✓ purrr     0.3.4
#> ── Conflicts ───────────────────────── tidymodels_conflicts() ──
#> x purrr::discard() masks scales::discard()
#> x dplyr::filter()  masks stats::filter()
#> x dplyr::lag()     masks stats::lag()
#> x recipes::step()  masks stats::step()
```

## Contributing

This project is released with a [Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.

  - For questions and discussions about tidymodels packages, modeling,
    and machine learning, please [post on RStudio
    Community](https://rstd.io/tidymodels-community).

  - Most issues will likely belong on the GitHub repo of an individual
    package. If you think you have encountered a bug with the tidymodels
    metapackage itself, please [submit an
    issue](https://github.com/tidymodels/tidymodels/issues).

  - Either way, learn how to create and share a
    [reprex](https://rstd.io/reprex) (a minimal, reproducible example),
    to clearly communicate about your code.

  - Check out further details on [contributing guidelines for tidymodels
    packages](https://www.tidymodels.org/contribute/) and [how to get
    help](https://www.tidymodels.org/help/).
