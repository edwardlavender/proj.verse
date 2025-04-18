
# `proj.verse`

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/patter)](https://CRAN.R-project.org/package=patter)

[`proj.verse`](https://github.com/edwardlavender/proj.verse) is an
umbrella package for a series of `proj` packages that support scientific
project development and management in `R`:

- [`proj.build`](https://github.com/edwardlavender/proj.build) provides
  build tools for functions and packages;
- [`proj.file`](https://github.com/edwardlavender/proj.file) provides
  file-system tools;
- [`proj.templates`](https://github.com/edwardlavender/proj.templates)
  sets up template RStudio Projects;
- [`proj.lapply`](https://github.com/edwardlavender/proj.lapply)
  provides iterative project workflows;

# Installation

The [`proj.verse`](https://github.com/edwardlavender/proj.verse) family
of packages can be installed with:

``` r
install.packages("devtools")
devtools::install_github("edwardlavender/proj.verse", 
                         dependencies = TRUE)
```

# Code of conduct

Please note that the
[`proj.verse`](https://github.com/edwardlavender/proj.verse) project is
released with a [Contributor Code of
Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
