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

## Types of an Object

* numeric
* character
* function
* data.frame
* logical

## Data Frames

Data Frames in R are similar to tables. Each column represents a variable and each row represents an observation.  
In other words, Data Frames are data sets that combine different types of objects into a single object.

**Loading a Data Frame**

`library(LibraryName)`  

`data(DataFrameName)`  

**Accessing the variables in the Data Frame is done with the `accessor` symbol which is `$`** 

i.e. `DataFrameName$variableName`  


## Functions in R

Function | Description
---------|------------
class() | Shows the type of an object
str () | Shows the structure of an object
head() | Shows the first 6 lines of a Data Frame
names() | Shows the names of the columns (variables)
length() | Shows the lenght of an object (number of observations)
levels() | Shows the levels (factors) of a categorical variable

