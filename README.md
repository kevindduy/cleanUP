Name: {cleanR}

Title:{A package for cleaning imported datasets in CSV format}

Description:
{The `cleanR` package provides a set of functions for cleaning and tidying up imported datasets in CSV format. It aims to remove missing values, convert data types, and handle duplicate rows and columns. This way, data analysis can be completed in a much smoother and quicker fashion.}

Installation:
You can install the latest version of `cleanR` from GitHub using the `devtools` package:
# install.packages("devtools")
devtools::install_github("kevindduy/cleanR")

Usage
library(cleanR)
dataframe <- read.csv("mydata.csv")
clean_data <- cleanR(dataframe)
View(clean_data)

Examples: 

distinctMe: Removes duplicate rows from the input dataframe.
dateMe: Converts columns containing date strings to date objects.
removeCol: Removes columns from the input dataframe.
replaceMe: Replaces old values with new values in specified columns of the input dataframe.
No_comma: Replaces commas with periods in specified numeric columns of the input dataframe.
BatmanTheme: Removes rows containing missing values from the input dataframe.

License: 
GPL-3
