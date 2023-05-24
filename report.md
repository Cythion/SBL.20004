# Metabolomics analysis report
SBL.20004 

24.05.2023

----
Group A
- Edouard BRUELHART
- Dominic STEINER
- Cyril JAGGI
----


## Introduction

Some words on the background of your projects.
Which plants did you select and why ?

Plants are one of the least mobile organisms on this planet and this can pose a problem when dealing with predators, because the option to flee is not really avaliable to them. Some plant are thus using a different strategy to deal with adversaries, toxic compounds. Toxins allow the plant to defend against potential predators by disincentivicing consumption. 

Aconitine is a neurotoxin, found in Aconitum and Delphinium plants, that acts on sodium-ion channels and inhibits conformational changes of the channel protein. This inhibition blocks membrane repolerization and without this membrane potential neurons are no longer able to work. Exposure to a high concentration of aconitine can lead to paralysis. 



## Material & Methods

### Sample collection

- Collection site(s):
    - Botanical garden of the University of Fribourg
- Collected species: 
    - Delphinium elatum
    - Delphinium caucasicum
    - Ranunculus auicomus
    - Ranunculus aconitifolius
    - Ranunculus repens
    - Ranunculus gramineus
    - Ranunculus arvensis
    - Ranunculus muricatus
    - Ranunculus acris friesianus
    - Aconitum carmichaelii
    - Aconitum napellus
    - Aconitum variegatum
    - Aconitum vulparia 
- iNaturalist entries.
    - [Observation Data](https://github.com/Cythion/SBL.20004/blob/main/data/observations-328542.csv)


### Sample preparation

1. 50mg dried plant leaves were weight into a 2mL Eppendorf tube.
2. 3 metal beads were loaded together with the leaves.
3. Lysed cells in ball mill for 2.5min at 25 Hertz 
4. 1.7mL extraction solvent (20% water, 80% MetOH, 0.1% formic acid) were added to each tube and mixed.
5. Samples were mixed again in the bell mill for 2.5min at 25 Hertz. 
6. Part of the supernatant was then transferred into a glass vial for the measurement and part was storred in another vial as reserve.
7. Samples were then measured in the LC-MS. 

### LCMS Analysis

- [LC conditions verbose](https://github.com/Cythion/SBL.20004/blob/main/lc_conditions.txt) 
    - The LC program consists of a 12min run in which a first gradiant ramps up the acetonitrile (ACN) composition from 5% up to 100% over the course of 6min. After that it keeps this up for another 2min before switching back to the initial 5% ACN / 95% water mixture. With the initial conditions the progam equilibrates for 4m and reaching the 12min mark. The flow rate and column temperature stay the same during the whole run, at 0.600mL/min and 40°C respectivly.
- [MS conditions verbose](https://github.com/Cythion/SBL.20004/blob/main/ms_conditions.txt)

### Data treatment

- Cytoscape 
- MZ-Mine 
- 

## Results


### MS1

How many features could you clean in your final peak list ?
A link to the final feature list (uploaded to github).
[Final feature list](https://github.com/Cythion/SBL.20004/blob/main/data/Final_Aligned_Feature_List.csv)

### Molecular Network

- Link to the [GNPS job](https://gnps.ucsd.edu/ProteoSAFe/status.jsp?task=54c7e463fe00492a9984c160219fb1d6).
- Not sure if this is the correct link!!! 
    - Link to the [GNPS identification table](https://gnps.ucsd.edu/ProteoSAFe/result.jsp?task=54c7e463fe00492a9984c160219fb1d6&view=view_all_annotations_DB).

## Conclusion

Some conclusion that you could get out of this preliminary study.

# References

Note that you can make a footnote like this [^1]

[^1]: Ref X
