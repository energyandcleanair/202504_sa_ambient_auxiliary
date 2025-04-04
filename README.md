# 202504_sa_ambient_auxiliary
Auxiliary analysis and plotting for South Africa ambient HIA


## Data source
Community Emissions Data System (CEDS) data downloaded from CREA emission portal, for South Africa for year 2022, for each species separately.

## Simplified sectors
The dataset contains a large number of sectors. Selected sectors to create simple combined categories:
 - Electricity production includes 'Electricity public [1A1a]' and 'Electricity autoproducer [1A1a]'
 - Fuel production includes '1a1bc other transformation [1A1bc]' and '1b1 fugitive solid fuels [1B1]'
 - Road transport includes '1a3b road [1A3b]'
 - Industry includes all the sectors listed under 'Industry (IND)' in Table 2 in https://doi.org/10.5194/essd-12-3413-2020
 - Others: all the rest

For SO2, road transport is included in Others.