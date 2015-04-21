# R-statements
* try(data(package = ""))
* data()                         -list all the datasets in the package
* data(....)                     -load ...
* rm(list=ls())                  -remove memory R
* ctrl+l                         -clear screen
* training$index <- seq(1, nrow(training))     -training is a "data.frame", assignment/add a column.
* require(...)              -load package.


# R problem
* library(AppliedPredictiveModeling)
  data(concrete)
  ---- data() find that mixtures(concrete), what does mixtures(concrete) mean? and how can I know if other datasets(concrete)?

* createDataPartition
  ---- createDataPartition(diagnosis, p = 0.50,list=FALSE)    class"matrix"
  ---- createDataPartition(...,p = 0.5)[[1]]                  class"numeric"
  ---- createDataPartition(..., p =0.5, list = TRUE)          class"list"
  what's the difference?
