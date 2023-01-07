# Interactive-maps-with-leafmap
Build interactive maps with leafmap on jupyter notebooks

# leafmap

## Description

This module provides functions for creating and manipulating maps using the Leaflet library.

## Installation

To install the leafmap module, use pip:

pip install leafmap


## Usage

To use the leafmap module, import it and create a Map object:

import leafmap

m = leafmap.Map(center=(-1.1993409323259936, 36.838099528619956), zoom_start=6)


This creates a new Map object centered at the given latitude and longitude and with a starting zoom level of 6.

To add a shapefile to the map as a layer, use the `add_shp` method:

in_shp = 'kenya_roads/Roads.shp'
m.add_shp(in_shp, layer_name='Roads')


This will add the shapefile located at 'kenya_roads/Roads.shp' to the map as a layer called 'Roads'. The shapefile is expected to contain geographic features (e.g. roads) that will be visualized on the map.

## Contributing

To contribute to the leafmap module, please submit a pull request on GitHub.

This README file provides an overview of the leafmap module and its functions, as well as instructions for installing and using the module. It also includes information on how to contribute to the development of the module. A README file is a useful resource for anyone using or working on the code, as it provides important information about the code and its purpose.
