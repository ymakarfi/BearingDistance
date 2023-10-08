# BearingDistance

Bearing Distance is a python based plugin for QGIS minimum version 3.18 that offers surveyors, cartographers and G.I.S analysts a method of generating bearing and distance of a polygon. 
This plugin also generates the coordinates of each corner of a polygon by creating a point shapefile.
The Bearing and Distance comes in a line shapelife and contains delail explanation within the attribute table.
# Contents and Usage

The Bearing & Distance plugin provides five (5) different options for generating Bearing and Distance of a polygon and the plugin is found in the Processing Toolbox window:

![pic1](https://github.com/ymakarfi/BearingDistance/assets/115046088/b872b691-0ae8-4d39-a362-28d96e2618e5)
![pic2](https://github.com/ymakarfi/BearingDistance/assets/115046088/ef2dafb0-4b2b-49c9-96a2-a1c8a767de0c)

### B & D(By Attribute_With Points)
This option allows a user to generate bearing and distance using a unique atrribute of a feature and also generate the bearing and distance using an existing point shapefile representing the beacons and its numbers.

![by attributes with points](https://github.com/ymakarfi/BearingDistance/assets/115046088/6b3baa86-e55d-41f7-8cb8-d747b9d9a122)

### B & D(By Attribute_Without Points)
This option allows a user to generate bearing and distance using a unique atrribute of a feature and also generate the bearing and distance using a default numbering which starts from Point 1, Point 2, Point 3,...... and therfore does not require a point shapefile.

![by attributes without points](https://github.com/ymakarfi/BearingDistance/assets/115046088/e48e91ab-1513-4a9d-a647-9124b820a730)

### B & D(Multiple Polygons_Without Points)
This option requires users to select multiple polygons they intend to generate bearing and distance for. This option will generate the bearing and distance using a default numbering which starts from Point 1, Point 2, Point 3,...... and therfore does not require a point shapefile.

![multiple without points](https://github.com/ymakarfi/BearingDistance/assets/115046088/d523daec-73c4-4d54-85b5-e128291f04c4)

### B & D(Single & Multiple Polygons_Without Points)
This option requires users to select a single polygon or multiple polygons they intend to generate bearing and distance for. This option will generate the bearing and distance using an existing point shapefile representing the beacons and its numbers.

![single and multiple with points](https://github.com/ymakarfi/BearingDistance/assets/115046088/13314a2a-5630-4694-8493-b12530a9d6b3)

### B & D(Single Polygon_Without Points)
This option requires users to select a single polygon  they intend to generate bearing and distance for.This option will generate the bearing and distance using a default numbering which starts from Point 1, Point 2, Point 3,...... and therfore does not require a point shapefile.

![single without points](https://github.com/ymakarfi/BearingDistance/assets/115046088/dd2a86e1-2edb-4539-8e37-be23f6d760ec)

# Installation
This plugin is only hosted here on github. If you desire to make use of it in QGIS then download the plugin folder a paste it in the plugin folder of your active profile folder.
