
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
#> 
#> → Package library at 'C:\Users\xpanmo\AppData\Local\Temp\RtmpYtjz04\temp_libpatha1e813576263'.
#> → Will update 1 package.
#> → Will download 1 package with unknown size.
#> + libminer 0.0.0.9000 → 0.0.0.9000 [bld][cmp][dl] (GitHub: c36a99c)
#> ℹ Getting 1 pkg with unknown size
#> ✔ Cached copy of libminer 0.0.0.9000 (source) is the latest build
#> ✔ Installed libminer 0.0.0.9000 (github::sinmojito/libminer@c36a99c) (67ms)
#> ✔ 1 pkg: upd 1 [2.3s]
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
#> 3 C:/Users/xpanmo/AppData/Local/Temp/RtmpYtjz04/temp_libpatha1e813576263
#>   n_packages
#> 1         30
#> 2        160
#> 3          1
```
