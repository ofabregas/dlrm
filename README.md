# dlrm
 Estimate the Model Logistic Regression dichotomous
<!-- README.md is generated from README.Rmd. Please edit that file -->

**NEWS**: Active development of dlrm has moved to the [experimental branch](https://github.com/jlvia1191/dlrm.git)

dlrm
========

An implementation of the Estimate the Model Logistic Regression dichotomous. 

*The development of this software was supported in part by NSF Postdoctoral Fellowship DMS-0903120*

Installation
------------

``` r
library(devtools)
install_github("jlvia1191/dlrm")
```

Example Usage
-------------

``` r
library(dlrm)
data(chdage)
dlrm(chdage$AGE,chdage$CHD)
```

![](README-chdage-example-1.png)
