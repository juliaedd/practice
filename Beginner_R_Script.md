Going through Jacob's R modules
M2 - Installing Packages and Reading Data

Installing tidyverse

``` r
install.packages(tidyverse)
library(tidyverse)

getwd()
setwd(~/data2) 
```
load data from files 
```r
wealth_data = read_csv("wealth_data.csv")
```