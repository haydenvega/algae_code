# Macroalgal functional trait data
This repository contains data and preliminary analysis for the Macroalgal functional trait project.
## General Information

1. Authors: 
- [Hayden Vega](haydenvega.github.io), haydenvega@ucsb.edu, University of California Santa Barbara
- [An Bui](https://an-bui.com/), an-bui@ucsb.edu, University of California Santa Barbara

2. Dates of data collection: 2023-06-27 - 2023-08-06

3. Location of data collection: **Specimens** were collected from California, USA at Santa Barbara Coastal Long-Term Ecological Research sites Mohawk (MOHK), Bullito (BULL), Carpenteria (CARP), and Naples (NAPL). **Measurements** were collected at the University of California Santa Barbara.

4. Funding Sources: Data collection supported by UCSB Coastal Fund (CF-202304-05858), California Sea Grant Prop 84 grant program (R/OPCOAH-2), SBC LTER (NSF-OCE 1831937), and UCSB FUERTE. 

## Sharing/Access Information

1. Licenses/restrictions placed on the data: This work is under a Creative Commons attribution license [(CC by 4.0 International)](https://creativecommons.org/licenses/by/4.0/)

2. Links to publications that cite or use the data: N/A

3. Links to other publicly accessible locations of the data: N/A

4. Links/relationships to ancillary data sets: N/A

5. Data was not derived from an alternate source

6. Recommended citation for this dataset: Vega, H. and A. Bui. 2025. Measurements of 7 morphological traits from 11 species of macroalgae from Southern California on fresh, herbarium-treated, and rehydrated individuals. 

## Data and File Overview

1. File list

| File Name|Description| 
|----------|-----------|
| final_functional_trait_data  |Contains the data for all specimens, traits, and treatments of the functional trait herbarium project. This includes seven sheets which correspond to data for a specific trait. | 
| final_functional_trait_data - max_height.csv    | Contains the final data for the height for all specimens and treatments.| 
|final_functional_trait_data - max_width.csv|Contains the final data for the width for all specimens and treatments. |
|final_functional_trait_data - perimeter.csv|Contains the final data for the perimeter of all specimens and treatments. |
|final_functional_trait_data - surf_area.csv|Contains the final data for the surface area of all specimens and treatments. |
| final_functional_trait_data - thickness_i.csv   |Contains the final data for the initial thickness of all specimens.|
|final_functional_trait_data - thickness_h.csv|Contains the final data for the herbarium thickness of all specimens.|
|final_functional_trait_data - thickness_r.csv|Contains the final data for the rehydrated thickness of all specimens.|
|final_functional_trait_data - volume.csv|Contains the final data for the volume of all specimens and treatments.|
|final_functional_trait_data - weight.csv|Contains the final data for the weight of all specimens and treatments.|

2. Relationship between files

- All the datasheets contain data for different traits. Each trait (maximum height, maximum width, surface area, perimeter, volume, and weight) is in its own sheet. The treatments included in each sheet are Initial (column suffix `_i`), Herbarium (column suffix `_h), and Rehydrated (column suffix `_r`).  
- The trait thickness varies from the above format and has one sheet per each treatment (Initial, Herbarium, and Rehydrated), for a total of three sheets.

3. There are **no** other versions of these data. 

## Methodological Information

1. Study goals

  Our goal was to investigate how herbarium and rehydration treatments affected seven common trait values (maximum height, maximum width, surface area, perimeter, volume, thickness, and weight) in eleven species of macroalgae (Egregia menziesii, Chondracanthus spp., Desmarestia ligulata, Dictyota spp., Gelidium robustum, Stephanocystis osmundacea, Rhodymenia spp., Coralina chilensis, Nienburgia andersoniana, Cryptopleura ruprechtiana, and Polyneura latissima).

2. Description of Methods

- Species Selection and Study Site
	From 06/27/23 to 08/07/23, we collected macroalgal individuals on SCUBA from Santa Barbara Coastal Long Term Ecological Research (SBC LTER) sites Mohawk (MOHK, Long: -119.72957, Lat: 34.3940708), Bullito (BULL, Long: -120.33349, Lat: 34.45850533), Carpinteria (CARP, Long: -119.5416933 Lat: 34.3916319), and Naples (NAPL, Long:-119.95154, Lat: 34.4221216). We collected samples from eleven species: Egregia menziesii, Chondracanthus spp., Desmarestia ligulata, Dictyota spp., Gelidium robustum, Stephanocystis osmundacea, Rhodymenia spp., Coralina chilensis, Nienburgia andersoniana, Cryptopleura ruprechtiana, and Polyneura latissima, which are common species in kelp forests and well-represented in herbarium collections. For species with complex structures, we collected three blades or branches for trait measurements, one from the bottom, middle, and top of the individual. We chose to measure traits on subsamples because many herbarium specimens preserve subsamples instead of the whole individual.

- Trait measurement
To investigate how a specimen’s functional traits change throughout the herbarium and rehydration process, we measured traits on each subsample  a total of three times: once when the specimen was freshly collected (Initial treatment), once after the specimen was pressed (Herbarium treatment), and once after the specimen was rehydrated (Rehydrated treatment). We measured maximum height, maximum width, thickness, weight, volume, surface area, and perimeter from each thallus, following standard trait protocols from Pérez-Harguindeguy et al. 2013. 
To collect maximum height, we measured the subsample  from the base to the tip. We measured maximum width by measuring the widest point of the subsample. We measured thickness using a digital caliper in ten haphazardly locations on the thallus, avoiding  the midrib, holdfast, or stipe if present. Next, we weighed each subsample to obtain initial weight. We then scanned each subsample using a flatbed scanner  and used a visual processing software (ImageJ) to measure perimeter and surface area. Lastly, we placed each subsample  into a graduated cylinder filled with DI water to measure volume via water displacement.
	
- Herbarium Treatment Methods
 To determine if fresh functional traits can be accurately predicted from an herbarium specimen, we preserved our specimens following standard herbarium trait protocols found in Smith 1971. We pressed each subsample in a cardboard press on a half sheet of acid-free archival herbarium paper. We compressed the cardboard press with weights as the algae were drying. We changed blotting paper and weighed each subsample  daily. We ended the pressing process once the weight of the subsample  did not change for three days. Once dry, the subsamples  were removed from the press for trait analysis. 

- Rehydration Treatment Methods
We rehydrated each subsample  to determine if functional traits of rehydrated specimens could predict the fresh functional trait values of an herbarium specimen. During rehydration, we fully submerged each subsample in filtered seawater (60 microns).Weighing each subsample every hour, we removed the subsample from the seawater once the weight did not change for three hours. Specimens were then patted dry with a cloth for subsequent trait measurement (as in Trait measurement section).
