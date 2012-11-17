## Introduction

This package distributes the code illustrating the use-cases described in the _Using R and Bioconductor for proteomics data analysis_ manuscript. 
The package illustrates how R and a selection of dedicated packages can be used to access mass spectrometry base proteomics data, manipulate and visualise it, how to process label-free and labelled quantitative data and how to analyse the quantitation data. 

The package will be updated beyond the content of the manuscript to keep up-to-date with progress in the area.

## Data and vignette

The package also distributes a set of function to access data from the ProteomeXchange `PXD000001` data, used in several examples, as well as a detailed document containing the exact code to reproduce all the analyses presented in the manuscript as well as other application examples. The latter document is called the package vignette, and can be accessed once the package is installed (see below) with the `RforProteomics()` function. Alternatively, the vignette can be downloaded alternatively as a pdf file [here](http://proteome.sysbiol.cam.ac.uk/lgatto/RforProteomics/RforProteomics.pdf). 

## Installation

The package is now available in [Bioconductor](http://bioconductor.org/packages/devel/data/experiment/html/RforProteomics.html). To install the package, start `R` and enter:


```r
source("http://bioconductor.org/biocLite.R")
biocLite("RforProteomics")
```

Once installed, the package with loaded with

```r
library("RforProteomics")
```

## Help

To obtain help or additional information about the `RforProteomics` package, please contact [me](http://proteome.sysbiol.cam.ac.uk/lgatto/). For help about the packages presented in the vignette or manuscript, please refer to the [R mailing list](https://stat.ethz.ch/mailman/listinfo/r-help), [Biodonductor mailing list](http://www.bioconductor.org/help/mailing-list/#bioconductor) (if the package is in Bioconductor) and/or the respective package authors. 
