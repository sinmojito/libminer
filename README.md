
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->

<!-- badges: end -->

The goal of libminer is to …

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("sinmojito/libminer")
```

## Example usage

To get a count of installed packages in each of your library locations,
optionally with the total sizes, use the `lib_summary()` function:

``` r
library(libminer)
lib_summary()
#>                                                                  Library
#> 1                                     C:/Program Files/R/R-4.6.1/library
#> 2                        C:/Users/xpanmo/AppData/Local/R/win-library/4.6
#> 3 C:/Users/xpanmo/AppData/Local/Temp/RtmpYtjz04/temp_libpatha1e835c72a38
#>   n_packages
#> 1         30
#> 2        160
#> 3          1
# specify `sizes = TRUE` to calculate the total size on disk of your packages
lib_summary(sizes = TRUE)
#>                                                                  Library
#> 1                                     C:/Program Files/R/R-4.6.1/library
#> 2                        C:/Users/xpanmo/AppData/Local/R/win-library/4.6
#> 3 C:/Users/xpanmo/AppData/Local/Temp/RtmpYtjz04/temp_libpatha1e835c72a38
#>   n_packages lib_size
#> 1         30   75.65M
#> 2        160  320.18M
#> 3          1   16.92K
```
