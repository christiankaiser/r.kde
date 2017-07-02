# r.kde example: Gridded population change data around Zurich, Switzerland

This is an example how to calculate a Gaussian Kernel Density for a population change dataset in Zurich, Switzerland.

The dataset contains the difference of population according to a simulated model at the level of a hectare (as a regular grid of 100x100 meters resolution).

The `popchange.img` file is a ERDAS Imagine file, the SRS is EPSG:21781 (CH1903/LV03).

To make a kernel density estimate on this raster file, run e.g.

```bash
r.kde --input popchange.img --output popchange_kde250.img --bandwidth 250
```

