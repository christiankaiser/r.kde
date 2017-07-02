# r.kde example: Gridded population data in Lausanne, Switzerland

This is an example how to calculate a Gaussian Kernel Density for a population dataset in Lausanne, Switzerland.

The dataset contains population data at the level of a hectare (as a regular grid of 100x100 meters resolution). The data is available in [Geostat dataset](http://www.geostat.admin.ch) from [Swiss Federal Statistical Office (SFSO)](http://www.bfs.admin.ch). The copyright and license from the original source applies.

The file `statpop_h15ptot.csv` is an extract from the Geostat file `STATPOP2015_HH.csv` after substraction of values in `STATPOP2015_HH_NOLOC.csv`. The extract covers a 43x30 km zone around the city of Lausanne.

`statpop_h15ptot.img` contains the same data but as a raster file in ERDAS Imagine format.


