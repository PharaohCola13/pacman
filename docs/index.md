---
title: "pacviz"
author: "Spencer Riley"
date: "last revised on 2021-07-10"
site: bookdown::gitbook
favicon: "favicon.ico"
documentclass: book
lot: yes
lof: yes
bibliography: [book.bib]
biblio-style: apalike
link-citations: yes
github-repo: PharaohCola13/pacviz
url: 'https\://pharaohcola13.github.io/pacviz/book'
output:
  bookdown::gitbook:
    dev: svglite
    highlight: monochrome
    config:
      download: pdf
      sharing:
        github: yes
        facebook: no
        google: yes
        twitter: no
        all: no
      fontsettings:
        theme: night
      info: no

---
<!-- default, tango, pygments, kate, monochrome, espresso, zenburn, and haddock -->
# About this document {-}

This is the documentation of the
[**pacviz**](https://cran.r-project.org/package=pacviz) package. Examples
in the book are generated under version 1.0.1.

<img src="images/cover.png" style="width:500px;border:2px solid black;" />

Session info:


```r
sessionInfo()
```

```
## R version 4.0.3 (2020-10-10)
## Platform: x86_64-pc-linux-gnu (64-bit)
## Running under: Ubuntu 20.04.2 LTS
## 
## Matrix products: default
## BLAS:   /opt/R-4.0.3/lib/libRblas.so
## LAPACK: /opt/R-4.0.3/lib/libRlapack.so
## 
## locale:
##  [1] LC_CTYPE=C.UTF-8       LC_NUMERIC=C           LC_TIME=C.UTF-8       
##  [4] LC_COLLATE=C.UTF-8     LC_MONETARY=C.UTF-8    LC_MESSAGES=C.UTF-8   
##  [7] LC_PAPER=C.UTF-8       LC_NAME=C              LC_ADDRESS=C          
## [10] LC_TELEPHONE=C         LC_MEASUREMENT=C.UTF-8 LC_IDENTIFICATION=C   
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## loaded via a namespace (and not attached):
##  [1] compiler_4.0.3    magrittr_2.0.1    bookdown_0.22     htmltools_0.5.1.1
##  [5] tools_4.0.3       yaml_2.2.1        stringi_1.6.2     rmarkdown_2.9    
##  [9] knitr_1.33        stringr_1.4.0     digest_0.6.27     xfun_0.24        
## [13] rlang_0.4.11      evaluate_0.14
```

## The Author {-}
The author and maintainer of this package is [Spencer Riley](https://pharaohcola13.github.io).