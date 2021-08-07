# MtBrocken-landing-strip-scenery
Custom scenery for FlightGear adding a landing strip on Mt. Brocken  

## Contents

This scenery makes available a small landing strip on the north-west side of Mt.Brocken. It covers _only_ the 3122034 tile (the one Mt. Brocen is on) - all other tiles have to be downloaded separately, for example with TerraSync.

## Installing

Simply `git clone` this repository:
```sh
git clone https://github.com/TheFGFSEagle/MtBrocken-landing-strip-scenery
```
or download it as a ZIP and unzip it to a location of your choice.

Then, in FGLauncher go to the `Addons` tab, and add the path to the directory you unzipped / cloned this repository to _including the `MtBrocken-landing-strip-scenery` at the end !  
After that, click on `Fly !` and enjoy !

Note: If you have just gray roads and buildings, you are probably using a too old version of FlightGear (I tested this scenery with version 2020.4.0), where `$FG_ROOT/Textures/osm2city/atlas_facades.png` was not yet present.  
Please check that - if you _do_ have that file, please [submit an Issue](https://github.com/TheFGFSEagle/MtBrocken-landing-strip-scenery/issues). 

## Sources

* Landuse data: download.geofabrik.com/europe/germany
* SRTM-1 Elevation data: usgs.gov
* `Roads/`, `Pylons/`, `Buildings`, and `Models/Brocken*`: Copied from my TerraSync folder
* `Airports/D/E/M/DEMB.*.xml`: generated from [DEMB.dat](./NavData/apt/DEMB.dat) using the [d-laser-fgtools](https://github.com/mherweg/d-laser-fgtools)
* `NavData/apt/DEMB.dat`: created with the XPlane WorldEditor
