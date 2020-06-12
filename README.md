catmaply <img src="man/figures/logo.png" align="right" height="192 px"/>
======================

[![R build status](https://github.com/yvesmauron/catmaply/workflows/R-CMD-check/badge.svg)](https://github.com/yvesmauron/catmaply/actions) [![codecov](https://codecov.io/gh/yvesmauron/catmaply/branch/master/graph/badge.svg)](https://codecov.io/gh/yvesmauron/catmaply) [![](https://img.shields.io/badge/lifecycle-development-blue.svg)](https://www.tidyverse.org/lifecycle/#development)


## Introduction

A heatmap a graphical representation of data that uses a system of color-coding to represent different values. Heatmaps are used in various forms of analytics, however, this R package specifically focuses on providing an efficient way for creating interactive heatmaps for categorical data. 

### Please submit feature requests

This package is still under active development. If you have features you would like to have added, please submit your suggestions (and bug-reports) at: <https://github.com/yvesmauron/catmaply/issues>

## News

tbd


### Code of conduct

Please note that this project is released with a [Contributor Code of Conduct](https://github.com/yvesmauron/catmaply/blob/master/CONDUCT.md). By participating in this project you agree to abide by its terms.



## Installation

To install the stable version on CRAN:

```r
install.packages('heatmaply')
```

To install the latest ("cutting-edge") GitHub version run:

```R

# good packages to install for this to work smoothly:

install.packages(c("Rcpp","ggplot2","munsell","htmltools","DBI","assertthat",
"gridExtra","digest","fpc","TSP","registry","gclus","gplots","RColorBrewer",
"stringr","labeling","yaml"))

# You'll need devtools
install.packages.2 <- function (pkg) if (!require(pkg)) install.packages(pkg);
install.packages.2('devtools')
# make sure you have Rtools installed first! if not, then run:
#install.packages('installr'); install.Rtools()

devtools::install_github("ropensci/plotly") # you will probably benefit from the latest version of plotly
devtools::install_github('talgalili/heatmaply')
```

And then you may load the package using:

```R
library("heatmaply")
```
