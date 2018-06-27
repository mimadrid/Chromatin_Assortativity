# Chromatin_Assortativity

Code to calculate chromatin assortativity (ChAs) of epigenomic features in chromatin interaction networks, including the ChIP-seq features and promoter-capture HiC (PCHIC) used in Pancaldi et al, 2016 (https://doi.org/10.1186/s13059-016-1003-3)

This GitHub repository contains an updated version of original code used in the paper that is available in FigShare (https://figshare.com/articles/ChromatinAssortativity/2009232/7). From now on, new developments will be incorporated in this GitHub repository.

## Setup
```
R
# See setRepositories() and getOption('repos') for more repositories
source("https://bioconductor.org/biocLite.R")
biocLite()
setRepositories(ind=2:5, addURLs=c(CRAN="https://cloud.r-project.org/"))
install.packages('packrat')
# packrat requires be initilized in the project folder
packrat::init()
```

## Usage
`Rscript Script/Process_Assort.r`
