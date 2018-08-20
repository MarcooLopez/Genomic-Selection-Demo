# Genomic Selection Demo

## Data
Data from CIMMYT’s Global Wheat Program. It contains information on 599 wheat lines whose grain
yield was evaluated in four environments (E1, low rainfall and
irrigated; E2, high rainfall; E3, low rainfall and high temperature;
and E4, low humidity and hot). 
Data is available for download in R-package 'BGLR' (Perez and de los Campos, 2014).

## R-packages installation
```
install.packages("BGLR")
install.packages("rrBLUP")
```

## Download data
```
library(BGLR)
data(wheat)
X <- wheat.X
Y <- wheat.Y
A <- wheat.A

# Visualize data
head(Y)
X[1:10,1:5]
```

## Analyses
* **[Single-environment](https://github.com/gdlc/STT465/blob/master/HW3.md)**


