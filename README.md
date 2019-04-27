
<!-- README.md is generated from README.Rmd. Please edit that file -->

# exuber <a href='https://kvasilopoulos.github.io/exuber'><img src='docs/logo.png' align="right" height="127.5" /></a>

[![Build
Status](https://travis-ci.org/kvasilopoulos/exuber.svg?branch=master)](https://travis-ci.org/kvasilopoulos/exuber)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/kvasilopoulos/exuber?branch=master&svg=true)](https://ci.appveyor.com/project/kvasilopoulos/exuber)
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/exuber)](https://cran.r-project.org/package=exuber)
[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
[![codecov](https://codecov.io/gh/kvasilopoulos/exuber/branch/master/graph/badge.svg)](https://codecov.io/gh/kvasilopoulos/exuber)

Testing for and dating periods of explosive dynamics (exuberance) in
time series using the univariate and panel recursive unit root tests
proposed by [Phillips et al. (2015)](https://doi.org/10.1111/iere.12132)
and [Pavlidis et al. (2016)](https://doi.org/10.1007/s11146-015-9531-2).
The recursive least-squares algorithm utilizes the matrix inversion
lemma to avoid matrix inversion which results in significant speed
improvements. Simulation of a variety of periodically-collapsing bubble
processes.

### Installation

``` r
# Install release version from CRAN
install.packages("exuber")

# Install development version from GitHub
# install.packages("devtools")
devtools::install_github("kvasilopoulos/exuber")
```

If you encounter a clear bug, please file a reproducible example on
[GitHub](https://github.com/kvasilopoulos/exuber/issues).

### Usage

Testing explosive time series is based on two principles, estimating
t-statistics and generating critical values.

For the former we use the `radf()` which is able to

For generating critical values we have several options. Firstly, the
package offers simulated critical values (up to 700 observations) in the
form of `data` that are obtain with the `mc_cv()` function.

The user has option

-----

Please note that the ‘exuber’ project is released with a [Contributor
Code of Conduct](.github/CODE_OF_CONDUCT.md). By contributing to this
project, you agree to abide by its terms.
