
# dynutils

[![Build
Status](https://travis-ci.org/dynverse/dynutils.svg?branch=master)](https://travis-ci.org/dynverse/dynutils)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/dynverse/dynutils?branch=master&svg=true)](https://ci.appveyor.com/project/dynverse/dynutils)
[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/dynutils)](https://cran.r-project.org/package=dynutils)
[![Coverage
Status](https://codecov.io/gh/dynverse/dynutils/branch/master/graph/badge.svg)](https://codecov.io/gh/dynverse/dynutils?branch=master)

Provides common functionality for the dynverse packages. An overview of
this functionality is available using the `?dynutils` command or in the
[examples
vignette](https://CRAN.R-project.org/package=dynutils/vignettes/functionality.html).

dynverse is created to support the development, execution, and
benchmarking of trajectory inference methods. For more information,
check out [dynverse.org](dynverse.org).

## Latest changes

Check out `news(package = "dynutils")` or [NEWS.md](inst/NEWS.md) for a
full list of
changes.

<!-- This section gets automatically generated from inst/NEWS.md, and also generates inst/NEWS -->

### Recent changes in dynutils 1.0.4 (unreleased)

  - BUG FIX: Fix for news with subsections.

  - FUNCTIONALITY: Added `%ifna%` infix operator.

### Recent changes in dynutils 1.0.3 (2019-05-02)

  - FUNCTIONALITY: Added `test_h5_installation()`.

  - BUG FIX: Added compatibility workaround for being able to read hdf5
    1.10.4 files on a hdf5 1.8.14 Windows platform (hhoeflin/hdf5r\#60).

  - FUNCTIONALITY: `calculate_distance()` and `calculate_similarity()`
    now support sparse matrix calculation thanks to proxyC\!

  - SMALL CHANGES: Remove dependencies: glue, Hmisc, devtools, testthat,
    tidyr.

## Dynverse dependencies

<!-- Generated by "update_dependency_graphs.R" in the main dynverse repo -->

![](man/figures/dependencies.png)
