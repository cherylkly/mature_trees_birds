# Data and Codes associated with Manuscript: Mature trees are important for birds in urban landscapes (in prep)
Authors: CKL Yong CKL, SKY Lum, P Gibbons

Aim: Evaluating the effectiveness of retaining mature trees for avian diversity in urban areas. 

This repository contains a data set of bird diversity indicators measured across 36 sites in 3 surveys. Site and landscape level features are included as predictors.

## Data Description:
### Survey Variables
* site_id
* survey_no

### Outcome Variables
* sp_rich               Overall species richness
* overall_abundance,    Overall abundance
* hollow_sp_rich        Overall species richness of hollow-dependent species
* hollow_use_abundance  Overall abdunance of hollow-dependent species


### Predictor Variables:
* big_tree_count:       Number of mature trees within the site
* rw_pres:              Presence of red wattlebird
* p_ground_grass:       Vegetation cover between 0-0.1m in height (%)
* p_low_shrubs:         Vegetation cover between 0.1-1m in height (%)
* p_midstorey:          Vegetation cover between 1-5m in height (%)
* area:                 Area (ha)
* tree_canopy_pct_200m: Proportion of canopy cover in a 200m buffer
* mt_count_200m:        Number of mature trees in a 200m buffer
* built_pct_200m:       Proportion of impervious surface cover in a 200m buffer (%)
* suburb:               Suburb
* dev_status:           Development status

### Predictors excluded from model due to high correlation:
* total_tree_count:   Number of trees within the site
* hollow_count:       Number of tree hollows
* shape_idx:          Shape Index
* road_traffic:       Largest adjacent road type
