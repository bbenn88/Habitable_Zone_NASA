# Habitable_Zone_NASA

install.packages("jsonlite")
install.packages("curl")
library(jsonlite)
     confirmed_planets <- fromJSON("https://exoplanetarchive.ipac.caltech.edu/cgi-bin/nstedAPI/nph-nstedAPI?             table=exomultpars&select=*&format=json")
     head(confirmed_planets)
