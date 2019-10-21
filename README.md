# MapBooklet
R package for generating map booklets.

## Installation

To install the current version, use `devtools`.

```R
devtools::install_github("MBalthasar/MapBooklet")
```

## Available Functions

The following functions are currently available and tested on Windows 10.

* `FishnetFunction()` This function creates a fishnet polygon from an input shapefile. The output fishnet will be reprojected to UTM.
* `BookletMaker()` This function uses a fishnet polygon to create a map booklet pdf based on a user ggplot. The booklet contains an overview map with the original ggplot and the fishnet polygon added on top, as well as sub-maps for each tile of the fishnet polygon.


## Example

![Overview](https://user-images.githubusercontent.com/33450966/67230216-273cf700-f43d-11e9-92aa-67bc5b7215e2.jpg)
