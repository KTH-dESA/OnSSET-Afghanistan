# OnSSET_Afghanistan

Python implementation of the Open Source Spatial Electrification Tool (OnSSET) for Afghanistan.

### Content

This repository contains the source code for the OnSSET model customized for the case study of Afghanistan. Note that a new version of the model that takes into account the effect of conflict has been added separately in January 2019. Code and files related to this version can be identified by the tag "Conflict" in their in the conflict branch. In both cases the model works in similar manner as described below.

### How-to-use Instructions 

1. Clone repository in a directory of your preference
2. Open onsset.py and runner.py in the IDE of your preference (Pycharm is suggested)
3. Install dependencies
4. Make sure that specs.csv and Afghanistan.csv files are in the same directory. Both files shall follow the format and naming convention as shown in the sample files in this repository. Parameter values can be changed accordingly
4. Run onsset.py and make sure there is no error
5. Run runner.py
  a. Select to calibrate the Afghanistan.csv as per instructions
  b. After calibration (taking place only once) start running scenarios as per instructions
5. After a scenario is run two output files will appear in the directory; one containing full results and another providing a summary.
6. Import the full result scv file into a GIS environment (QGIS, ArcMap) to vizualize the results.

### Cautions

The first input file (specs.csv) contains most of the inputs parameters of the analysis such as total population, urban population ratio, diesel price etc.

The second input file (Afghanistan.csv) contains all the GIS information (21 columns) for the settlements to be included in the analysis. This csv file has by convention the same name with the country it represents (e.g. in this case "Afghanistan.csv").

The sample files in this repository provide low granularity and shall only be used as test beds. KTH dESA has prepared a proper version of the Afghanistan.csv file able to run the electrification analysis with 1 km spatial resolution. Access information can be found below.

### Supplementary material

- The GIS layers that have been used in this analysis are available at [Energydata.info](https://energydata.info/).
- Input file in higher granularity (1 km spatial resolution) can be downloaded from [here](https://drive.google.com/drive/folders/1ejRtY2CHmlXWYkV4NBjsgkC8BXJxFiSz?usp=sharing).
- More information regarding running OnSSET is available at [OnSSET manual](http://www.onsset.org/get-started.html).
- A GIS based least cost electrification analysis for Afghanistan is available [here](https://energypedia.info/wiki/File:A_GIS_approach_to_electrification_planning_in_Afghanistan.pdf).
- An academic publication supporting this work is available [here](https://www.mdpi.com/2071-1050/12/3/777).

- For any additional information please contact the KTH team [here.](http://www.onsset.org/contact--forum.html)
