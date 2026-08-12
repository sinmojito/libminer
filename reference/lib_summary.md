# R Library Summary

Provides a brief summary of the package libraries on your machine

## Usage

``` r
lib_summary(sizes = FALSE)
```

## Arguments

- sizes:

  Should the sizes of the libraries be calculated?

## Value

A data.frame containing the count of packages in each of the user's
libraries. A `lib_size` column is included if `sizes = TRUE`.

A `data.frame` containing the count of packages in each of the user's
libraries

## Examples

``` r
lib_summary()
#>                           Library n_packages
#> 1 /home/runner/work/_temp/Library         67
#> 2      /opt/R/4.6.1/lib/R/library         29
#> 3 /opt/R/4.6.1/lib/R/site-library          1
```
