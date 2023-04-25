# SBL.20004.2023



## 👋 Hello !

This repo groups material for the SBL.20004 teachings in 2023 spring semester. See https://www.unifr.ch/timetable/en/course.html?show=104013

## 🔗 Useful links

- Course material:

Most of the material is accessible at the following Zenodo repository: https://doi.org/10.5281/zenodo.6379085

- Discussion and exchanges around the course :

Please have a look at the Forum here : https://github.com/commons-teaching/forum/discussions

- Working with markdown files (the format of the document your are reading now)

https://docs.github.com/en/get-started/writing-on-github


# Tasks for the practical

## Upload to iNaturalist

All the observations of your collected samples should be uploaded to the iNaturalist DBGI project.
For this you will need to :

-  create an iNaturalist account at https://www.inaturalist.org/
-  join the Digital Botanical Gardens Initiative at https://www.inaturalist.org/projects/digital-botanical-gardens-initiative
-  upload your observations. Remind to activate the geolocalisation of your phone before making the pictures !

## Preparation of injection sample list 

In order to launch the injections of the samples you have prepared you will need to establish a sample list sequence. This file can be formatted as csv and here is a template example. 
Please reuse [this template](https://github.com/commons-teaching/SBL.20004.2022/blob/main/sequence_template.csv) by erasing all samples and adding yours. You can simply modify the column named "File Name", we will take care of the other fields at the moment of the injection.
For your sample naming please respect the following pattern :
**YYYYMMDD_groupX_DBGI_XX_XX_XX** (for example 20220503_groupA_DBGI_01_03_15)

## Data treatment

### Establish a metadata file for your sample set

In order to map additional metadata on your treated dataset you will need to prepare a metadata file. 
Please respect the template available [here](
https://github.com/commons-teaching/SBL.20004.2022/blob/main/metadata_template.txt) 

The following are mandatory:

- the header of the column containing the filename should be 'filename'
- the filnames should _**exactly**_ match the ones your have created for your sample list sequence (see above)
- you should add a column with the binomial denomination of all your samples (except for blanks in this case just write ND)
- add a column with the iNaturalist observation id of your sample (except for blanks in this case just write ND). Just paste the link corresponding to your sample e.g. https://www.inaturalist.org/observations/112939194
- the file should be saved as a [Tab separated values](https://en.wikipedia.org/wiki/Tab-separated_values) file. 

Apart form this you can add any additional metadata you would like to map. E.g extraction method, medicinal use, group according to genetic analysis etc.

👉 Upload both the sample list and the corresponding metadata file to your own github repository. Create this last one if needed.


### MS Data

Profiling data on the Q-Exactive are available here https://drive.switch.ch/index.php/s/4vlNZhrD0QcDJnh

### Requirements for data treatment session

- Download Proteowizard https://proteowizard.sourceforge.io/
- Download MzMine 2.53 https://github.com/mzmine/mzmine2/releases
- Download Filezilla https://filezilla-project.org/download.php?type=client
- Download Cytoscape https://cytoscape.org/ Download version 3.82 as the latest one still has bugs regarding color mapping options https://github.com/cytoscape/cytoscape/releases/3.8.2/

### Docuemntation

Have a detailed look at the excellent FBMN documentation https://ccms-ucsd.github.io/GNPSDocumentation/featurebasedmolecularnetworking-with-mzmine2/

## Report preparation

Please prepare your report and upload it to your own group github repository. The report template is available [here](https://github.com/commons-teaching/SBL.20004.2022/blob/23ea9493b07940f0592a2004e6caacd9e66ab359/report_template.md)



