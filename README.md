# Age and Sex Matching Using Propensity Score Matching

## Overview
This repository demonstrates a reproducible R workflow for constructing age- and sex-balanced comparison groups between **Familial** and **Sporadic** individuals using propensity score matching (PSM).

## Objective
To reduce baseline demographic differences in observational data and create comparable groups prior to downstream analyses.

## Methodology
- Propensity score estimated using:
  - Age (continuous)
  - Sex (binary)
- Matching performed using:
  - 1:1 nearest-neighbour matching
  - Without replacement
- Balance assessed using standardized mean differences (SMD < 0.10).

## Results
The procedure matched:

87 Familial individuals  
to  
87 Sporadic individuals

All age and sex imbalance was eliminated, producing a well-balanced analytical cohort.

## Reproducibility
The full workflow is available in:

`Age_Sex_Matching.Rmd`

## Data Availability
Original data are not publicly shared due to confidentiality.  
The workflow can be applied to any dataset with a group indicator, age, and sex.

## RPubs Report
https://rpubs.com/Samadou_Tchakondo/age-sex-matching-familial-sporadic

##  Author
**Samadou Tchakondo**  
MSc Biostatistics & Epidemiology  
SRM Institute of Science and Technology  


## License

This project is shared for academic and reproducible research purposes.
