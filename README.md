# lineament-extraction-MHHC-python
Original MHHC algorithm for spatial clustering of the line segments as a tool for lineament extraction.

The lineament is a linear feature describing discontinuity in a landscape. The lineament extraction is not an easy problem. Recently, an automatic approach based on multi-hillshade hierarchic clustering has been developed. An important part of this approach is the spatial line segment clustering. This paper presents a new algorithm for this clustering, based on a facility location algorithm. The results of implementation show acceleration in comparison with its predecessor.

### Requirements: 
* python 2.7.13 - check [Python](https://www.python.org/downloads/)
* arcpy - check [ArcPy](http://pro.arcgis.com/en/pro-app/arcpy/get-started/what-is-arcpy-.htm)
* Input data - places in same folder as ``central_cmd.py`` in folder ``Input`` (check [LineamentExtraction-MHHC-Input](https://github.com/OKaas/LineamentExtraction-MHHC-Input))

### Usage:
* ``$python central_cmd.py <input file path>``
    
###### Where:
* ``<input file path>``  - path to input file
    
###### Example:
* ``$python central_cmd.py c_zm_r0_200``

### Input data:
* [MHHC-Python-Input](https://github.com/OKaas/LineamentExtraction-MHHC-Input)