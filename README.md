# OnSSET_Afghanistan

Python implementation of the Open Source Spatial Electrification Tool (OnSSET) for Afghanistan.

### Content

A new version of the OnSSET electrification model that takes into account the effect of conflict has been added separately in January 2019. Code and files related to this version can be identified by the tag "Conflict" in their name. The model works otherwise in similar manner.

This repository contains a jupyter notebook which allow for a quick, screening electrification analysis using a simplified version of OnSSET. Sample files of Malawi are available for testing. Note, that both code and input files are only indicative and are only used here to showcase OnSSET's functionality.

### How-to-use Instructions 

1. Clone repository in a directory of your preference
2. Start Jupyter notebook in the directory 
3. Extract the zipped Malawi csv file in the directory
4. Install dependencies
5. Run blocks sequentially 

### Cautions

The first file (specs) contains most of the inputs parameters of the analysis (such as total population, urban population ratio, diesel price etc.) is by convention "specs" and you can find it usually within the db file serving as directory.

The second file contains all the GIS information (21 columns) for the settlements to be included in the analysis. This csv file has by convention the same name with the country it represents (e.g. in this case "Afghanistan.csv"). When prepared, this file shall be placed within the bd file as well.

KTH dESA has prepared two versions of the Afghanistan.csv file able to run the electrification analysis with 1 and 10 km spatial resolution respectively. 



### Supplementary material

- The GIS layers that have been used in this analysis are available at [Energydata.info](https://energydata.info/).

- Input files in higher granularity (1 and 10 km spatial resolution) can be downloaded at [Energydata.info](https://energydata.info/).

For any additional information please contact the KTH team [here.](http://www.onsset.org/contact--forum.html)

