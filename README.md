<!-- README.md is generated from README.Rmd. Please edit that file -->
wildlifedetectR
===============

`wildlifedetectR` provides a collection of functions for running typical
wildlife forensic tests. This package is in development.

-   Test code:

``` r
    # install.packages("devtools")
    # building vignettes might take some time. Set build_vignettes = FALSE for a quick download.
    
    devtools::install_github("elhumble/wildlifedetectR", build_vignettes = TRUE)
    
    # Individualisation tutorial
    
    library(wildlifedetectR)
    ?individualisation
    
    data(BadgerRefPop)
    data(BadgerTrace)
    individualisation(db = BadgerRefPop,
                      unknown = BadgerTrace,
                      Th = 0.1,
                      allele_freq = T,
                      known_alleles = T)
```

### Authors

E Humble & K Ewart
