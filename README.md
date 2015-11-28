rUnemploymentData
===

This R Package contains data and visualization functions for USA unemployment data. The data was scraped from the 
US Bureau of Labor Statistics (BLS) in January 2015. The functions which scraped the data are also in this package, 
which allows you to reproduce and verify the dataset yourself.

## Development

I blog about this package's development [here](http://www.arilamstein.com/blog).

# Installation

To install the package from CRAN type:

```
install.packages("rUnemploymentData")
```

To install the package from github type:

```
# install.packages("devtools")
library(devtools)
install_github("trulia/rUnemploymentData")
library(rUnemploymentData)
```

# State Unemployment Data

The state unemployment data covers 2000-2013 and is in the data.frame `?df_state_unemployment_data`.  Further 
information can be found in the vignette [US State Unemployment Data](http://cran.r-project.org/web/packages/rUnemploymentData/vignettes/a-state.html).

# County Unemployment Data

The county unemployment data covers 1990-2013 and is in the data.frame `?df_county_unemployment_data`.  Further 
information can be found in the vignette [US County Unemployment Data](http://cran.r-project.org/web/packages/rUnemploymentData/vignettes/b-county.html).

# Reproducibility

The data in this package was scraped from the BLS website on January 4, 2014. The scripts which scraped the data are available in `get_state_unemployment_df` and `get_county_unemployment_df`.
