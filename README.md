# Habitable_Zone_NASA

install.packages("jsonlite")
install.packages("curl")

library(jsonlite)

confirmed_planets <- fromJSON("https://exoplanetarchive.ipac.caltech.edu/cgi-bin/nstedAPI/nph-nstedAPI?table=compositepars&select=fpl_hostname,fpl_name,fpl_smax,fst_lum,fst_mass,fpl_bmasse&format=json")
     
head(confirmed_planets)
