
### RAM Legacy Stock Boundary Database

#### Description

The RAM Legacy Stock Boundary Database provides the spatial boundaries for 685 non-salmon stocks in the [RAM Legacy Stock Assessment Database](https://www.ramlegacy.org/) (v.4.41; Ricard et al. 2012).

Each version of the Stock Boundary Database provides the following folders:

1. **PNGs** - maps illustrating location of the stock
2. **Rasters** - R raster files saved as Rds files
3. **Shapefiles** - GIS shapefiles

The shapefiles and rasters are projected using the following coordinate system:

* WGS 1984 Mollweide in meters
* CRS("+proj=moll +lon_0=0 +x_0=0 +y_0=0 +ellps=WGS84 +units=m +no_defs")

<br>

#### Reporting errors

Please report incorrectly delineated stocks or any other issues encountered when using the database by [creating an issue](https://help.github.com/articles/creating-an-issue/) in this GitHub repository.

<br>

#### Brief methods description

Boundaries were delineated by: 

1. Merging the statistical/management areas used to define the assessment area;
2. Digitizing the assessment area directly from the stock assessment; or
3. Clipping the managing country’s exclusive economic zone or the managing agency’s area of competence to the geographical reference points provided in the stock assessment. 

In the USA and Australia, information on the geographic distribution of each species was used to further constrain stock boundaries.

A more detailed summary of methods is available here

<br>

#### References

Ricard D, Minto C, Jensen OP, Baum JK (2012) Examining the knowledge base and status of commercially exploited marine species with the RAM Legacy Stock Assessment Database. *Fish & Fisheries* 13(4): 380-398.

<br>

#### Papers using this database

Free CM, Thorson JT, Pinsky ML, Oken KL, Wiedenmann J, Jensen OP. Impacts of historical warming on marine fisheries production. In press at *Science*.

