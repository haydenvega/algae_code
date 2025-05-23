# Macroalgal functional trait data
This repository contains data and preliminary analysis for the Macroalgal functional trait project.
# Table of Contents

  - [General Information](https://github.com/haydenvega/algae_code?tab=readme-ov-file#general-information)
    - [1. Authors](https://github.com/haydenvega/algae_code?tab=readme-ov-file#1-authors)
    - [2. Dates of data collection](https://github.com/haydenvega/algae_code?tab=readme-ov-file#2-dates-of-data-collection)
    - [3. Location of data collection](https://github.com/haydenvega/algae_code?tab=readme-ov-file#3-location-of-data-collection)
    - [4. Funding Sources](https://github.com/haydenvega/algae_code?tab=readme-ov-file#4-funding-sources)
  - [Sharing/Access Information](https://github.com/haydenvega/algae_code?tab=readme-ov-file#sharingaccess-information)
    - [1. Licenses/restrictions placed on the data](https://github.com/haydenvega/algae_code?tab=readme-ov-file#1-licensesrestrictions-placed-on-the-data)
    - [2. Links to publications that cite or use the data](https://github.com/haydenvega/algae_code?tab=readme-ov-file#2-links-to-publications-that-cite-or-use-the-data)
    - [3. Links to other publicly accessible locations of the data](https://github.com/haydenvega/algae_code?tab=readme-ov-file#3-links-to-other-publicly-accessible-locations-of-the-data)
    - [4. Links/relationships to ancillary datasets](https://github.com/haydenvega/algae_code?tab=readme-ov-file#4-linksrelationships-to-ancillary-datasets)
    - [5. Data Derivation](https://github.com/haydenvega/algae_code?tab=readme-ov-file#5-data-derivation)
    - [6. Recommended citation for this dataset](https://github.com/haydenvega/algae_code?tab=readme-ov-file#6-recommended-citation-for-this-dataset)
  - [Data and File Overview](https://github.com/haydenvega/algae_code?tab=readme-ov-file#data-and-file-overview)
    - [1. File list](https://github.com/haydenvega/algae_code?tab=readme-ov-file#1-file-list)
    - [2. Relationship between files](https://github.com/haydenvega/algae_code?tab=readme-ov-file#2-relationship-between-files)
    - [3. Data Versions](https://github.com/haydenvega/algae_code?tab=readme-ov-file#3-data-versions)
  - [Methodological Information](https://github.com/haydenvega/algae_code?tab=readme-ov-file#methodological-information)
    - [1. Study Goals](https://github.com/haydenvega/algae_code?tab=readme-ov-file#1-study-goals)
    - [2. Description of Methods](https://github.com/haydenvega/algae_code?tab=readme-ov-file#2-description-of-methods)
    - [3. Methods for Processing the Data](https://github.com/haydenvega/algae_code?tab=readme-ov-file#3-methods-for-processing-the-data)
    - [4. Descrption of quality assurance](https://github.com/haydenvega/algae_code?tab=readme-ov-file#4-describe-any-quality-assurance-procedures-performed-on-the-data)
  - [Data Specific Information for: final_functional_trait_data - XXX.csv](https://github.com/haydenvega/algae_code?tab=readme-ov-file#data-specific-information-for--final_functional_trait_data---xxxxcsv)
    - [1. Variables](https://github.com/haydenvega/algae_code?tab=readme-ov-file#1-variables)
    - [2. Rows](https://github.com/haydenvega/algae_code?tab=readme-ov-file#2-rows)
    - [3. Variable List](https://github.com/haydenvega/algae_code?tab=readme-ov-file#3-variable-list)
    - [4. Missing Data](https://github.com/haydenvega/algae_code?tab=readme-ov-file#4-missing-data)
  - [Citations](https://github.com/haydenvega/algae_code?tab=readme-ov-file#citations)
## General Information

### 1. Authors

- [Hayden Vega](haydenvega.github.io), haydenvega@ucsb.edu, University of California Santa Barbara
- [An Bui](https://an-bui.com/), an-bui@ucsb.edu, University of California Santa Barbara

### 2. Dates of data collection

2023-06-27 - 2023-08-06

### 3. Location of data collection

**Specimens** were collected from California, USA at Santa Barbara Coastal Long-Term Ecological Research sites Mohawk (MOHK), Bullito (BULL), Carpenteria (CARP), and Naples (NAPL). **Measurements** were collected at the University of California Santa Barbara.

### 4. Funding Sources

Data collection was supported by UCSB Coastal Fund (CF-202304-05858), California Sea Grant Prop 84 grant program (R/OPCOAH-2), SBC LTER (NSF-OCE 1831937), and UCSB FUERTE. 

## Sharing/Access Information

### 1. Licenses/restrictions placed on the data

This work is under a Creative Commons attribution license [(CC by 4.0 International)](https://creativecommons.org/licenses/by/4.0/)

### 2. Links to publications that cite or use the data

N/A

### 3. Links to other publicly accessible locations of the data

N/A

### 4. Links/relationships to ancillary datasets

N/A

### 5. Data Derivation

Data was not derived from an alternate source.

### 6. Recommended citation for this dataset

Vega, H. and A. Bui. 2025. Measurements of 7 morphological traits from 11 species of macroalgae from Southern California on fresh, herbarium-treated, and rehydrated individuals. 

## Data and File Overview

### 1. File list

```plaintext
.
├── README.html
├── README.md
├── algae_code.Rproj
├── data
│   ├── final_trait_data
│   │   ├── final_functional_trait_data - max_height.csv    # final height data
│   │   ├── final_functional_trait_data - max_width.csv     # final width data
│   │   ├── final_functional_trait_data - perimeter.csv     # final perimeter data
│   │   ├── final_functional_trait_data - surf_area.csv     # final surface area data
│   │   ├── final_functional_trait_data - thickness_h.csv   # final thickness data for the herbarium treatment
│   │   ├── final_functional_trait_data - thickness_i.csv   # final thickness data for initial values
│   │   ├── final_functional_trait_data - thickness_r.csv   # final thickness data for the rehydrated treatment
│   │   ├── final_functional_trait_data - volume.csv        # final volume data 
│   │   └── final_functional_trait_data - weight.csv        # final weight data
│   └── preliminary_data
├── figures
│   ├── herbarium_treatment
│   └── rehydrate_treatment
└── regression_figure_code
    ├── clean_mult_reg.Rmd
    ├── clean_mult_reg.html
    ├── clean_mult_reg_files
    └── old-codes
```

### 2. Relationships between files

All datasheets contain data for different traits. Each trait (maximum height, maximum width, surface area, perimeter, volume, and weight) is in its own sheet. The treatments included in each sheet are Initial: column suffix_i, Herbarium: column suffix_h, and Rehydrated: column suffix_r.  

The measurements for thickness vary from the above format. For thickness, there is one sheet per treatment (Initial, Herbarium, and Rehydrated), for a total of three sheets.

### 3. Data Versions

There are **no** other versions of these data. 

## Methodological Information

### 1. Study goals

  Our goal was to investigate how herbarium and rehydration treatments affected seven common trait values (maximum height, maximum width, surface area, perimeter, volume, thickness, and weight) in eleven species of macroalgae (_Egregia menziesii_, _Chondracanthus_ spp., _Desmarestia ligulata_, _Dictyota_ spp., _Gelidium robustum_, _Stephanocystis osmundacea_, _Rhodymenia_ spp., _Corallina chilensis_, _Nienburgia andersoniana_, _Cryptopleura ruprechtiana_, and _Polyneura latissima_).

### 2. Description of Methods

#### Species Selection and Study Site

From 06/27/23 to 08/07/23, we collected macroalgal individuals on SCUBA from Santa Barbara Coastal Long Term Ecological Research (SBC LTER) sites Mohawk (MOHK, Long: -119.72957, Lat: 34.3940708), Bullito (BULL, Long: -120.33349, Lat: 34.45850533), Carpinteria (CARP, Long: -119.5416933 Lat: 34.3916319), and Naples (NAPL, Long:-119.95154, Lat: 34.4221216). We collected samples from eleven species that are common in kelp forests and well-represented in herbarium collections. For species with complex structures, we collected three blades or branches for trait measurements, one from the bottom, middle, and top of the individual. We chose to measure traits on subsamples because many herbarium specimens preserve subsamples instead of the whole individual.

#### Trait measurement

To investigate how a specimen’s functional traits change throughout the herbarium and rehydration process, we measured traits on each subsample a total of three times: once when the specimen was freshly collected (Initial treatment), once after the specimen was pressed (Herbarium treatment), and once after the specimen was rehydrated (Rehydrated treatment). We measured maximum height, maximum width, thickness, weight, volume, surface area, and perimeter from each thallus, following standard trait protocols from [Pérez-Harguindeguy et al. 2013](http://dx.doi.org/10.1071/BT12225).  

To collect maximum height, we measured the subsample from the base to the tip. We measured maximum width by measuring the widest point of the subsample. We measured thickness using a digital caliper in ten haphazardly locations on the thallus, avoiding  the midrib, holdfast, or stipe if present. Next, we weighed each subsample to obtain initial weight. We then scanned each subsample using a flatbed scanner and used a visual processing software (ImageJ) to measure perimeter and surface area. Lastly, we placed each subsample into a graduated cylinder filled with DI water to measure volume via water displacement.
	
#### Herbarium Treatment Methods
 
To determine if fresh functional traits can be accurately predicted from an herbarium specimen, we preserved our specimens following standard herbarium trait protocols found in [Smith 1971](https://catalog.hathitrust.org/Record/011392994). We pressed each subsample in a cardboard press on a half sheet of acid-free archival herbarium paper. We compressed the cardboard press with weights as the algae were drying. We changed blotting paper and weighed each subsample daily. We ended the pressing process once the weight of the subsample did not change for three days. Once dry, the subsamples were removed from the press for trait analysis. 

#### Rehydration Treatment Methods

We rehydrated each subsample to determine if functional traits of rehydrated specimens could predict the fresh functional trait values of an herbarium specimen. During rehydration, we fully submerged each subsample in filtered seawater (60 microns). Weighing each subsample every hour, we removed the subsample from the seawater once the weight did not change for three hours. Specimens were then patted dry with a cloth for subsequent trait measurement (as in Trait measurement section).

### 3. Methods for Processing the Data

The data were recorded manually on paper and then transferred into digitized spreadsheets.

### 4. Describe any quality-assurance procedures performed on the data

The data were double checked for correctness and missing values were noted in this [document](https://docs.google.com/spreadsheets/d/1i3OTJ4KeNQvkKKWyZZq07TolnpbGl9uUha3ALMi2XxI/edit?usp=sharing). Missing values occurred when specimens were too fragile to be measured. 

## Data Specific Information for : final_functional_trait_data - XXXX.csv

### 1. Variables

There are a total of nine csv files. Each file contains the data for a unique functional trait and contains five variables: specimen_id, column suffix_i, column suffix_h, column_suffix r, species, and notes.

- The variable **specimen_id** is formatted as follows: date collected-site collected-individual ID-subsample ID. For example, 062723-MOHK-018-H corresponds to a specimen collected on June 27, 2023 at the site MOHK from individual 018, sub sample H.
- The variables column suffix_i, column suffix_h, and column suffix_r are formatted specifically for each sheet. The column suffix portion of the variable corresponds to the trait followed by it's unit of measurement (e.g. height_cm). The i,h,and r within the variables stand for initial, herbarium, and rehydrate, respectively. These denote the treatment the data belong to.
- The variable **species** is the species of macroalgae that each observation belongs to. There are eleven abbreviations for species: BF, CC, CO, CYOS, DL, DP, EGME, GR, NAND, POLA, and R. A key is below. 

    | Species Abbreviation |        Species Name       | 
    |----------------------|---------------------------|  
    |BF                    |*Cryptopleura ruprechtiana*|
    |CC                    |*Chondracanthus spp.*      |
    |CO                    |*Corallina chilensis*      |
    |CYOS                  |*Stephanocystis osmundacea*|
    |DL                    |*Desmarestia ligulata*     |
    |DP                    |*Dictyota spp.*            |
    |EGME                  |*Egregia menziesii*        |
    |GR                    |*Gelidium robustum*        |
    |NAND                  |*Nienburgia andersoniana*  |
    |POLA                  |*Polyneura latissima*      |
    |R                     |*Rhodymenia spp.*          |
    
### 2. Rows

Each row contains the data for a unique individual. There are 175 individuals included in each sheet. 

### 3. Variable List

|Variable    |  Description                                                    | 
|------------|-----------------------------------------------------------------|  
|specimen_id | A unique ID for each specimen. Specimen Ids are formatted as MM DD YY-site-individual-subsample.|
|species     | Species of an individual. Entries are species abbreviations.    |
|notes       | Notes about specimens and how they were collected.              |
|height_cm_i | Initial height of each individual in cm.                        |
|height_cm_h | Herbarium height of each individual in cm.                      |
|height_cm_r | Rehydrated height of each individual in cm.                     |
|width_cm_i  | Initial width of each individual in cm.                         |
|width_cm_r  | Rehydrated width of each individual in cm.                      |
|width_cm_h  | Herbarium width of each individual in cm.                       |
|thick_cm_i  | Initial average thickness of each individual in cm.             |
|thick_cm_h  | Herbarium average thickness of each individual in cm.           |
|thick_cm_r  | Rehydrated average thickness of each individual in cm.          |
|surf_cm_h   | Herbarium surface area of each specimen in cm2.                 |
|surf_cm_r   | Rehydrated surface area of each specimen in cm2.                |
|surf_cm_i   | Initial surface area of each individual in cm2.                 |
|per_cm_r    | Rehydrated perimeter of each specimen in cm.                    |
|per_cm_h    | Herbarium perimeter of each specimen in cm.                     |
|per_cm_i    | Initial perimeter of each specimen in cm.                       |
|vol_ml_h    | Herbarium volume of each specimen in mL.                        |
|vol_ml_i    | Initial volume of each specimen in mL.                          |
|vol_ml_r    | Rehydrated volume of each specimen in mL.                       |
|weight_g_h  | Herbarium weight of each specimen in g.                         |
|weight_g_i  | Initial weight of each specimen in g.                           |
|weight_g_r  | Rehydrated weight of each specimen in g.                        |

### 4. Missing Data

Missing observations are reported as “NA”, and occurred when the specimen was too fragile to handle. All missing observations are described [here](https://docs.google.com/spreadsheets/d/1i3OTJ4KeNQvkKKWyZZq07TolnpbGl9uUha3ALMi2XxI/edit?usp=sharing). 

## Citations

  Pérez-Harguindeguy, N., S. Díaz, E. Garnier, S. Lavorel, H. Poorter, P. Jaureguiberry, M. S. Bret-Harte, W. K. Cornwell, J. M. Craine, D. E. Gurvich, C. Urcelay, E. J. Veneklaas, P. B. Reich, L. Poorter, I. J. Wright, P. Ray, L. Enrico, J. G. Pausas, A. C. de Vos, N. Buchmann, G. Funes, F. Quétier, J. G. Hodgson, K. Thompson, H. D. Morgan, H. ter Steege, L. Sack, B. Blonder, P. Poschlod, M. V. Vaieretti, G. Conti, A. C. Staver, S. Aquino, and J. H. C. Cornelissen. 2013. New handbook for standardised measurement of plant functional traits worldwide. Australian Journal of Botany 61:167.
  
  Smith, C. E. 1971. Preparing herbarium specimens of vascular plants. Agricultural Research Service, U.S. Dept. of Agriculture; [for sale by the Supt. of Docs., U.S. Govt. Print. Off., [Washington].
