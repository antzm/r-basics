# R-Basics

## R-Basics for statistics

Notes on statistics and the R language  

## Installing R
First of all, you need to install R  
[Comprehensive R Archive Network](https://cran.r-project.org/)

## Installing RStudio (IDE)
After installing R, it is recommended to install RStudio  
[RStudio Website](https://www.rstudio.com/products/rstudio/download/)

## Variable Declarations

We can assign values to variables using the `=` operator:
```
a = 1
b = 2
c = 3
```
or preferably, we could use the `<-` operator:
```
a <- 1
b <- 2
c <- 3
```

## Installing Packages
```
install.packages("packageName")

```
Installation takes place only once for each package we need


After installing a package, we can use it in our script 

by loading the library of that package:

```
library(packageName)
```

To see all the packages we have installed:

```
installed.packages()
```