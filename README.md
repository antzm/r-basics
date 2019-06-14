# R-Basics

## R-Basics for statistics

Notes on statistics and the R language  

## Installing R
First of all, you need to install R  
[Comprehensive R Archive Network](https://cran.r-project.org/)

## Installing RStudio (IDE)
After installing R, it is recommended to install RStudio  
[RStudio Website](https://www.rstudio.com/products/rstudio/download/)

## Online R Consoles

If you don't want to install R, you can still use R through various online R consoles like:

* https://rextester.com/l/r_online_compiler

## Variable Declarations

We can assign values to variables using the `=` operator:
```
a = 1
b = 2
c = 3
```
or preferably, we could better use the `<-` operator:
```
a <- 1
b <- 2
c <- 3
```
To see the value that is stored in a variable, we could either just type the name of the variable:

```
a
```
Or, we we could use the function `print()`
```
print(a)
```
While, to see all the variables in our workspace, we could use the ls() function:
```
ls()
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
str() | Shows the structure of an object
head() | Shows the first 6 lines of a Data Frame
names() | Shows the names of the columns (variables)
length() | Shows the lenght of an object (number of observations)
levels() | Shows the levels (factors) of a categorical variable
data() | lists the available data sets in the package "datasets"


## Mathematical Functions in R

Mathematical Function | Description
----------------------|------------
a^b | a to the power of b
sqrt() | Square root
log() | log with base e (natural log)
log(a, b) | log a with base = b
exp() | e to the power of ... (exponential)

## Functions Help

* help("function_name")

or  

* ?function_name

To get the list of arguments needed for a function, we could use:

```
args(function_name)
```

To get help for the arithmetic operators:

* help("+")

or  

* ?"+"

To get help for the logical operators:

* help(">")

or  

* ?">"

# Symbols in R

Symbols | Description
---------|------------
pi | the cosntant π = 3.14159...
inf | infinity


# Comments in R

Comments can be written by starting our text with a `#` symbol

i.e. `# this is a comment in R`


