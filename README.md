
# `proj.verse`

[![Project Status: Active – The project has reached a stable, usable
state and is being actively
developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/patter)](https://CRAN.R-project.org/package=patter)

`proj.verse` is an umbrella package for a series of `proj` packages that
support scientific project development and management in `R`:

- `proj.build` provides build tools for functions and packages;
- `proj.file` provides file-system tools;
- `proj.template` sets up new RStudio Projects;
- `proj.lapply` provides iterative project workflows;
- `proj.verse` is is the umbrella package;

# Installation

The `proj.verse` family of packages can be installed with:

``` r
install.packages("devtools")
devtools::install_github("edwardlavender/proj.verse", 
                         dependencies = TRUE)
```

# Code of conduct

Please note that the `proj.verse` project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
