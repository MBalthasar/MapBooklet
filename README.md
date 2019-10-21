# MapBooklet
A toolbox for manipulating spatial data.

## Installation

To install the current version, use `devtools`.

```R
devtools::install_github("MBalthasar/MapBooklet")
```

## Available Functions

The following functions are currently available and tested on Windows 10.

* `FishnetFunction()` This function creates a fishnet polygon from an input shapefile. The output fishnet will be reprojected to UTM.
* `BookletMaker()` This function uses a fishnet polygon to create a map booklet pdf based on a user ggplot. The booklet contains an overview map with the original ggplot and the fishnet polygon added on top, as well as sub-maps for each tile of the fishnet polygon.
