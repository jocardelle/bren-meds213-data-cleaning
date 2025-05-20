# Cleaning the shorebird survey data 


## The data set

ARCTIC SHOREBIRD DEMOGRAPHICS NETWORK [https://doi.org/10.18739/A2222R68W](https://doi.org/10.18739/A2222R68W)

Data set hosted by the [NSF Arctic Data Center](https://arcticdata.io) data repository 

Field data on shorebird ecology and environmental conditions were collected from 1993-2014 at 16 field sites in Alaska, Canada, and Russia.

![Shorebird, copyright NYT](https://static01.nyt.com/images/2017/09/10/nyregion/10NATURE1/10NATURE1-superJumbo.jpg?quality=75&auto=webp)

Data were not collected every year at all sites. Studies of the population ecology of these birds included nest-monitoring to determine the timing of reproduction and reproductive success; live capture of birds to collect blood samples, feathers, and fecal samples for investigations of population structure and pathogens; banding of birds to determine annual survival rates; resighting of color-banded birds to determine space use and site fidelity; and use of light-sensitive geolocators to investigate migratory movements. 

Data on climatic conditions, prey abundance, and predators were also collected. Environmental data included weather stations that recorded daily climatic conditions, surveys of seasonal snowmelt, weekly sampling of terrestrial and aquatic invertebrates that are prey of shorebirds, live trapping of small mammals (alternate prey for shorebird predators), and daily counts of potential predators (jaegers, falcons, foxes). Detailed field methods for each year are available in the `ASDN_protocol_201X.pdf` files. All research was conducted under permits from relevant federal, state, and university authorities.

See `01_ASDN_Readme.txt` provided in the [course data repository](https://github.com/UCSB-Library-Research-Data-Services/bren-meds213-spring-2024-class-data) for full metadata information about this data set.

## DATA & FILE OVERVIEW

1. File List:
```
├── README.md
├── data
|   ├── processed
|    ├── all_cover_fixed_JosephineCardelle.csv
|    └── snow_cover.csv
|   ├── raw
|    ├── 01_ASDN_Readme.txt
|    ├── ASDN_Daily_species.csv
|    └── ASDN_Snow_survery.csv
├── docs
|   ├── data-cleaning_files/libs
|    ├── bootstrap
|    ├── clipboard
|    ├── quarto-html
|   └── data-cleaning.html
├── data-cleaning_empty.qmd
└── eds213_data_cleaning_assign_JosephineCardelle.qmd
```

- `data/processed/all_cover_fixed_JosephineCardelle.csv`: CSV file containing the cleaned version of periodic records of snow cover remaining at the site
- `data/processed/snow_cover.csv`: CSV file containing a cleaned snow_cover column of periodic records of snow cover remaining at the site
- `data/raw/01_ASDN_Readme.txt`: README file containing information relating to the raw data files
- `data/raw/ASDN_Daily_species.csv`: Record of the species (birds and mammals) encountered during field work each day at each site
- `data/raw/ASDN_Snow_survey.csv`: Periodic records of snow cover remaining at the site
- `data-cleaning_empty.qmd`: file containing cleaning process for `data/processed/snow_cover.csv`
- `eds213_data_cleaning_assign_JosephineCardelle.qmd`: file containing cleaning process for `data/processed/all_cover_fixed_JosephineCardelle.csv`

2. Relationship between files, if important:
   
- The files in the `data/processed` contain cleaned versions of `data/raw/ASDN_Snow_survey.csv`.

4. Additional related data collected that was not included in the current
data package:

The following lists data files available on the ASDN page at 
the NSF Arctic Data Center (https://arcticdata.io) and is a .csv file with prefix "ASDN_"):
	- Bird_captures
	- Bird_eggs
	- Bird_nests
	- Bird_resights
	- Bird_sexes
	- Camp_info
	- Camp_staff
	- Daily_pred_lemm
	- Daily_species
	- Daily_species_effort
	- Geodata
	- Invert_biomass
	- Lemming_counts
	- Lemming_nests
	- Lemming_trap
	- Pred_nests
	- Pred_point_counts
	- Snow_survey
	- Study_Plot	(KMZ file)
	- Surface_water
	- Weather_HOBO
	- Weather_precip_manual
	- Weather_snow_manual

6. Are there multiple versions of the dataset? 

- Yes, there are multiple versions of the Snow_survey dataset in this repository. The raw version can be found at `data/raw/ASDN_Snow_survey.csv`. A version with a cleaned snow_cover column can be found at `data/processed/snow_cover.csv`. A version with cleaned snow_cover, water_cover, land_cover, and total_cover columns can be found at `data/processed/all_cover_fixed_JosephineCardelle.csv`.

## DATA-SPECIFIC INFORMATION FOR:

### For the file  data/processed/all_cover_fixed_YOURNAME.csv : 

1. Number of variables:

2. Number of cases/rows:

3. Variable List: <list variable name(s), description(s), unit(s)and value 
labels as appropriate for each>

4. Missing data codes: <list code/symbol and definition>

5. Specialized formats or other abbreviations used:

## SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data:

2. Links to publications that cite or use the data:

3. Links to other publicly accessible locations of the data:

4. Links/relationships to ancillary data sets: <any supplementary data sources 
that support analysis or classification of the datasets, eg., plant taxonomy table.)>

5. Was data derived from another source? If yes, list source(s): <list citations 
to original sources>

6. Recommended citation for the project:
