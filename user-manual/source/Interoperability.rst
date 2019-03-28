Interoperability
=================================

The GEP is expected to be a part of a continuous ‘data discovery’ process. That process will – in partnership – discover and develop new data via remote sensing, machine learning, development of new theory and modelling. New data will be compiled, processed in models and new information produced during the operation of the GEP. To ensure that this data can easily be shared, standards for its form and description, as well as GEP data ‘handling protocols’ have been developed and hereafter suggested.

Data guidelines
************************************

Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enim in turpis pulvinar facilisis.

Modelling processes guidelines
***********************************

The GEP is being designed with interoperability in mind, such that it can ship inputs to and receive outputs from a wide array of models. For reasons of transparency, repeatability, and auditability at least one set of model results by country will be developed using the Open Source Spatial Electrification Tool (OnSSET.org). To meet in-country demands, advances will be made in the OnSSET.org model itself. However, as OnSSET.org is an open source project – contributions from outside the GEP working team to its development are welcomed.

The following paragraphs provide a brief overview of the modelling guidelines that can be use to replicate and update the Electrification Investment Scenarios available in **GEP "Explorer"**.

EIS development pipeline
+++++++++++++++++++++++++++++++++++++++++

The KTH team has developed a methodology to generate the scenarios using the standards established as part of the Global Electrification Platform (GEP).  The following document describes the steps and methodologies used in order to create scenarios in line with what has been done in the GEP.

**1. Collection of datasets**

The KTH-team has put down a list of datasets that are either crucial or helpful during the analysis. A list compiling all the datasets are available here in the GIS input data section and here.
The list includes the crucial datasets as well as the optional datasets. The KTH-team has indicated the datasets available and used for the Malawi case study.

**2. Creation of population clusters**

After collecting the datasets, the clusters are created. The clusters are population clusters and therefore dependent on the population dataset that is available. The KTH-team has developed two methodologies for this process. The methodologies are described in depth here.

**3. GIS processing**

The collected datasets are processed in a GIS-interface. QGIS is the recommended software to use as the KTH team has prepared a plugin for QGIS available here. Instruction for how to run the plugin can be found here.

The extraction code will generate a csv file used as input for the OnSSET model. The current version of the extraction code (as of February) creates 24 columns. However, in order to run the OnSSET algorithm a number of additional columns have to be added. The columns needed are all included here. The green rows represent data that are generated directly from the plugin, the other columns have to be generated manually by the user.

**4. Creating the specs-file**

OnSSET takes two input files; the GIS extracted file described above and a specs-file. The data included in the specs-file is described here.

**5. Calibration of input files**

OnSSET includes an embedded calibration algorithm that is used if and when a calibration is needed for the model to fit reality. More information on the calibration process is available here.

**6. Define levers**

Define the values for the different levers that you would like to use for your scenarios. Documentation on the different levers is available here and here.

**7. Run and analyze scenarios**

The GEP is currently using a modified version of OnSSET 2018 release available here. This model yields 144 EISs. Documentation on what is included in the output file can be found here.


Setting up and Ingesting EIS data on GEP "Explorer" (locally)
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Information is available `here. <http://devseed.com/gep-docs/>`_

Updating process guidelines
***********************************
The annual suite of Electrification Investment Scenarios (EIS’s) will include a set of least cost investment scenarios for each target country. The scenarios will be defined by different levels of desired use, the expected costs of technology, and other ‘levers’ etc. These updates will reflect advances in: algorithms and models; improvements in data input; as well as increased scenarios defined by increasingly relevant and available ‘levers’.

In addition, every year an updated version of GEP “Explorer” and GEP “Scenario Generator” will be released. A process will be set up for active updating of these with outreach to partners such that the latest available modelling, data and analysis is both used and compatible with the GEP.  Similarly, each year, advances in standards and updated teaching material will be released.

The first pre-release of the GEP2018 is planned for the *Optimus Community Summer School* in June 2019. Successive releases of the GEP will be made in the last quarter of each year. Calls for input to the GEP will be made and received by August each year.


