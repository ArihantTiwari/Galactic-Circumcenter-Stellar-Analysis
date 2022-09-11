# Stellar Analysis of the Galactic Circumcenter 

## Overview

The Galactic Center is the rotational center and the barycenter of the Milky Way galaxy. Its
center contains a supermassive black-hole (SMBH) of about 4 million solar masses, named Sagit-
tarius A*. It is a compact radio source, and is about 8 Kilo-parsecs away from Earth in the
direction of the Sagittarius Constellation.
The stellar population of about 10 million in a radius of one parsec around the galactic center is
dominated by red giants, substantial amount of supergiants and Wolf-Rayet stars.
In this stellar analysis I have used two approaches to extract data that represent parts of the
galaxy as a function of stellar variables. The two types of datasets used are:

1. Beam Data: A (1o × 1o) square window centered at the RA and DEC coordinates of the
Galactic Center is specified. All the stars, binary stars and the white dwarfs that fall into
this window are extracted to form the Beam Data. This is because this data set contains all
the mentioned sources in a beam with a cross-sectional area of (1 degree)2 from the Earth towards
the Galactic Center.
2. Sphere Data: A sphere of radius 300 parsecs, centered at the Galactic Center is specified
and all the stars, binary stars and white dwarfs falling into this region are extracted. The
query parameters were determined using trigonometric formulations including the inverse
of tan of the ratio of the radius of desired sphere around the center of the galaxy and the
distance of the galactic center from the earth (approximated to be 8 kilo-parsecs).

## Files

- `Galactic_Stellar_Analysys.ipynb`: Main code file containing the Data Query and Plotting.
- `data`: Directory containing all the Dataframes for the Analysis
> - `Shpere.csv`: Sphere Dataframe
> - `Beam.csv`: Beam Dataframe
- `Report.pdf`: Interpretation and Data analysis Report
- 'images`: Directory containing all the Images used in tht Jupyter Notebooks

## Conclusion

The final interpretation presented in this project are my own, and have no guarantee of being true. If you find any error in the files, please drop an email at arihant3601@gmail.com. All suggestions and comments are welcome!

*Nasadiye Sthito Manah*

**Arihant Tiwari**
