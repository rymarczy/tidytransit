[![CRAN
status](http://www.r-pkg.org/badges/version-ago/tidytransit?)](https://cran.r-project.org/package=tidytransit)
[![Project Status: Active](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active) 
[![](https://cranlogs.r-pkg.org/badges/tidytransit)](https://cran.r-project.org/package=tidytransit)
[![](https://cranlogs.r-pkg.org/badges/grand-total/tidytransit?color=lightgrey)](https://cran.r-project.org/package=tidytransit)
[![R build
status](https://github.com/r-transit/tidytransit/workflows/R-CMD-check/badge.svg)](https://github.com/r-transit/tidytransit/actions?query=workflow%3AR-CMD-check)
[![codecov](https://codecov.io/gh/r-transit/tidytransit/branch/master/graph/badge.svg)](https://codecov.io/gh/r-transit/tidytransit)

# tidytransit

Use tidytransit to map transit stops and routes, calculate travel times and transit
frequencies, and validate transit feeds. Tidytransit reads the 
[General Transit Feed Specification](https://gtfs.org/) into 
[tidyverse](https://tibble.tidyverse.org/) and 
[simple features](https://en.wikipedia.org/wiki/Simple_Features) data frames. 
Tidytransit can be used to:
- [read GTFS feeds into R](http://tidytransit.r-transit.org/reference/read_gtfs.html)
- [calculate travel times between transit stops](http://tidytransit.r-transit.org/reference/travel_times.html)
- [convert stops and routes to sf data frames](http://tidytransit.r-transit.org/reference/gtfs_as_sf.html)
- [validate transit feeds and more](http://tidytransit.r-transit.org/reference/index.html)

Have a look at the following vignettes to see how tidytransit can be used to analyse a feed:

- [the tutorial](http://tidytransit.r-transit.org/articles/introduction.html) 
- [calendar and service patterns](http://tidytransit.r-transit.org/articles/servicepatterns.html)
- [create time tables for stops](http://tidytransit.r-transit.org/articles/timetable.html)
- [frequency and headway calculations](http://tidytransit.r-transit.org/articles/frequency.html)  

## Installation

This package requires a working installation of
[sf](https://github.com/r-spatial/sf#installing).

Install tidytransit from CRAN:

``` r
install.packages('tidytransit')
```

For the development version from Github:

```r
# install.packages("devtools")
devtools::install_github("r-transit/tidytransit")
```

## GTFS-related packages

-   [`gtfsio`](https://github.com/r-transit/gtfsio) R package to read and write gtfs feeds, tidytransit builds on gtfsio
-   [`gtfstools`](https://github.com/ipeaGIT/gtfstools) Tools for editing and analysing transit feeds
-   [`gtfsrouter`](https://github.com/ATFutures/gtfs-router) Package for public transport routing 
-   [`gtfs2gps`](https://github.com/ipeaGIT/gtfs2gps) Converting public transport data from GTFS format to GPS-like records


## Contributing

Please feel free to issue a pull request or [open an issue](https://github.com/r-transit/tidytransit/issues/new).
