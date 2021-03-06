
## RcppArmadillo [![Build Status](https://travis-ci.org/RcppCore/RcppArmadillo.svg)](https://travis-ci.org/RcppCore/RcppArmadillo) [![License](http://img.shields.io/badge/license-GPL%20%28%3E=%202%29-brightgreen.svg?style=flat)](http://www.gnu.org/licenses/gpl-2.0.html) [![CRAN](http://www.r-pkg.org/badges/version/RcppArmadillo)](https://cran.r-project.org/package=RcppArmadillo) [![Downloads](http://cranlogs.r-pkg.org/badges/RcppArmadillo?color=brightgreen)](http://www.r-pkg.org/pkg/RcppArmadillo)

R and Armadillo via Rcpp

### Overview

[Armadillo](http://arma.sf.net) is a templated C++ linear algebra library
written by Conrad Sanderson that aims towards a good balance between speed and ease of use. Integer,
floating point and complex numbers are supported, as well as a subset of
trigonometric and statistics functions. Various matrix decompositions are
provided through optional integration with LAPACK and ATLAS libraries.
 
A delayed evaluation approach is employed (during compile time) to combine 
several operations into one, and to reduce (or eliminate) the need for 
temporaries. This is accomplished through recursive templates and template 
meta-programming.   

This library is useful if C++ has been decided as the language of choice 
(due to speed and/or integration capabilities), rather than another language.

The RcppArmadillo package includes the header files from the templated
Armadillo library. Thus users do not need to install Armadillo itself in
order to use RcppArmadillo. 
 
This Armadillo integration provides a nice illustration of the 
capabilities of the [Rcpp](http://www.rcpp.org) package for seamless R and
C++ integration. 

### Status

The package is under active development with releases to
[CRAN](https://cran.r-project.org) about once a month.

### Documentation

The package contains a pdf vignette which is a pre-print of the [paper by
Eddelbuettel and Sanderson](http://dx.doi.org/10.1016/j.csda.2013.02.005) 
in CSDA (2014).

### Authors

Romain Francois, Dirk Eddelbuettel and Doug Bates

### License

GPL (>= 2)
