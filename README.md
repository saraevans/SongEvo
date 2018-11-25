# SongEvo

SongEvo simulates the cultural evolution of quantitative traits of bird song. SongEvo is an individual- (agent-) based model. SongEvo is spatially-explicit and can be parameterized with, and tested against, measured song data. Functions are available for model implementation, sensitivity analyses, parameter optimization, model validation, and hypothesis testing. See the [vignette](https://github.com/raydanner/SongEvo/tree/master/vignettes) for examples. 

## Install 'SongEvo' from GitHub

In order to install the vignette along with the package use the following code with `build_vignettes = TRUE`. 
**Note** it takes quite a bit longer to download the package when `build_vignettes = TRUE`.

```{r eval = FALSE}
install.packages("devtools")
library(devtools)
devtools::install_github("raydanner/SongEvo", build_vignettes = TRUE)
library(SongEvo)
```

```{r,warning=FALSE,message=FALSE,echo=FALSE}
library(SongEvo)
```

## Issues

Find a bug?  Want to request an enhancement? Check out our [issues](https://github.com/raydanner/SongEvo/issues) page!


