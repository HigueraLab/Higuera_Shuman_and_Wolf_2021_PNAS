## Data and code for "Rocky Mountain subalpine forests now burning more than any time in recent millennia"

## Overview

This archive includes data and scripts needed to reproduce the analyses in Higuera, Shuman, and Wolf (2021). After extracting the .zip archive, there are three directories: code, data, and figures. Contents in each directory are describe in detail below.

**Contact:** Philip Higuera, University of Montana PaleoEcology and Fire Ecology Lab, https://www.cfc.umt.edu/research/paleoecologylab/, philip.higuera@umontana.edu

### Citation Information -- DATA AND CODE
Higuera, Philip; Shuman, Bryan; Wolf, Kyra (2021), Data and Code for "Rocky Mountain subalpine forests now burning more than any time in recent millennia," PNAS, Dryad, Dataset, https://doi.org/10.5061/dryad.rfj6q579n

##### Original Reference - *please cite if you use data, code, or figures in your own work*
Higuera, P.E., B.N. Shuman, and K.D. Wolf. 2021. Rocky Mountain subalpine forests now burning more than any time in recent millennia. Proceedings of the National Academy of Sciences. https://doi.org/10.1073/pnas.2103135118

#### Contents

## 1. CODE

#### File: Figures_all_script.m
Written for MATLAB software (*.m file type; www.mathworks.com), and fully commented, including dependencies. 

#### File: RCode_ContemporaryFRPCalc.R
Written for R software (*.R file type), and fully commented, including dependencies. 

#### Subdirectory: "html"
Matlab "markdown" html page that can be used to walk through the script "Figures_all_script.m", which includes the figures embedded in the html page. 

## 2. DATA

###  Paleo-fire datasets:
####  1. SouthernRockies_site_metadata.csv
####  2. Calder_et_al_CharResults.csv
####  3. ROMO_CharResults.csv
####  4. Minckley_et_al_LWH_CharResults.csv
###  Spatial datasets: study area, focal study area, fire perimiters
####  5. ecoregp075_M331H_M331I.shp
####  6. FocalStudyArea_SubalpineConiferForestESPP_WGS84.tif
####  7. FocalStudyArea_SubalpineConiferForestESP_Albers.tif -- Subalpine forest vegetation raster (projected)
####  8. SRockies_Fires_1984_2020_WGS84.shp -- Fire perimeters
####  9. SRockies_Fires_1984_2020_Albers.shp -- Fire perimeters (projected)
###  Summary statistics: contemporary annual area burned, fire rotation periods from tree-ring reconstructions
####  10. AreaBurned_Ecoregion_FocalStudy_1984_2020.csv -- Area burned statistics 
####  11. Dendro_FRP_Calculations.xlsx -- Spreadsheet with calculations of fire rotation periods from four published tree-ring fire-history reconstructions 
###  Climate datasets: contemporary VPD, paleo-temperature records
####  12. EcoSec_M331H_M331I_Mean_VPD_MaySep_1979_2020.csv -- VPD data for Southern Rockies study area, averaged across space. 
####  13. GrandLake_Mean_VPD_MaySep_1980_2020.csv -- VPD data for Grand Lake, CO, as point representation for focal study area. 
####  14. trouet2013nam480pollen.csv -- Paleoclimate (temperature) reconstruction by Trouet et al. (2013).
####  15. Mann08_nhcru_eiv_composite_updatedCRU_v102520.csv -- Paleoclimate (temperature) reconstruction by Mann et al. (2008), update with CRU data from 2009-2020. 


## 3. FIGURES

Figures in .tiff format, uncompressed at 600 dpi. 

#### Files:
* Fig_1.tiff
* Fig_2.tiff
* Fig_S1.tiff
* Fig_S2.tiff
* Fig_S3.tiff
