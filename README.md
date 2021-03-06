# zipcodes
US Zip Codes Database from simplemaps (Basic)

[![CodeFactor](https://www.codefactor.io/repository/github/martinctc/zipcodes/badge)](https://www.codefactor.io/repository/github/martinctc/zipcodes)

This a simple R package that provides access to the US Zip Codes database from **simplemaps**. Use the dataset in this package to join and look up information for US zip codes, latitudes and longitudes, etc. 

---

### Installation

You can install the latest development version from GitHub with:

```
install.packages("devtools")
devtools::install_github("martinctc/zipcodes")
```

### Accessing the data

You can then access the zipcode data via the following:
```
zipcodes::uszips
```
...or assign it to a variable:

```
zips <- zipcodes::uszips
```
