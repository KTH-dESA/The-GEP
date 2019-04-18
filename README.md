# The GEP "Scenario Generator" 
Source code and supplementary material related to the Global Electrification Platform (GEP)

### Content

This repository contains a jupyter notebook which allows for a quick replication of electrification scenarios as seen in the GEP "Explorer". Sample files of Malawi are available for testing.

### How-to-use Instructions 

1. Clone repository in a directory at your local machine
2. Open jupyter notebook in the directory
3. Make sure all dependencies are installed; a list is available at the top of each .ipynb file
4. Make sure that the GIS input file (e.g. Malawi.csv) is configured properly and located in the same directory. The file shall follow the format and naming convention as indicated in this repository. Parameter values can be changed accordingly.
4. Start executing comand boxed in the notebook in order
5. After a scenario run is complete, two output files will appear in the directory; one containing full results and another providing a summary.
6. Import the full result .csv file into a GIS environment (QGIS, ArcMap) to vizualize the results.

### Cautions

The GIS input file (Malawi.csv) contains all the GIS information (21 columns) for the settlements to be included in the analysis. Information on how to prepare and inform this file are available [here](https://the-gep-user-manual.readthedocs.io/en/latest/index.html)

The GEP "Scenario Generator" prepares electrification scenario files in the format necessary so as to facilitate ingestion into the GEP "Explorer". Note, however, that ingestion requires that all environments are set up properly. Further documentation on how to set up the GEP "Explorer" environment locally is available [here](https://the-gep-user-manual.readthedocs.io/en/latest/index.html).

### Supplementary material

- For any additional information please contact the GEP team [here.](https://the-gep-user-manual.readthedocs.io/en/latest/Contact.html)

