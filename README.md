### Datasets
For this assessment you have been provided a single dataset, `gourds.csv`. This dataset contains the results of the Great Pumpkin Commonwealth Weighoff for the years 2013 through 2021. The columns of this dataframe are contained in the data dictionary.md file.

Your notebook should be able to be run error-free from top to bottom, including the `read_csv` calls.

### Data Dictionary
|variable          |description |
|:-----------------|:-----------|
|year              |Competition year|
|type_id           |Type of gourd. See the types below |
|weight            |Weight |
|place             |Place/ranking |
|grower_name       |Name of grower |
|city              |City|
|state_prov        |State/Province|
|country           |Country|
|gpc_site          |GPC site |
|seed_mother       |Seed mother|
|pollinator_father |Father |
|ott               |Over the top inches, can be used to estimate weight |
|est_weight        |Estimated weight in lbs |
|variety           |Variety of pumpkin |

Types: F = "Field Pumpkin", P = "Giant Pumpkin", S = "Giant Squash", W = "Giant Watermelon", L = "Long Gourd" (length in inches, not weight in pounds), T = Tomato
