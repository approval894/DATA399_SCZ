# DATA399_SCZ
DATA 399 Group Project between Saul, Cody, and Zachary

# Topic: Deforestation From Mining
Mining is a major driver of deforestation, as large areas of forest get cleared for open pits, roads, processing facilities, and worker housing. In addition to these direct impacts, mining-related infrastructure can open previously inaccessible forest areas, leading to indirect deforestation through settlement, agriculture, and logging. Both large-scale and artisanal or small-scale mining contribute to forest loss; however, small-scale mining can be particularly harmful because it is more difficult to monitor and regulate, and is often done illegally.

This problem affects multiple stakeholders and rightsholders in different ways. Mining companies and financial institutions may view deforestation as a necessary trade-off to meet production goals and contractual requirements. In contrast, Indigenous and local communities experience deforestation as a direct threat to their land, livelihoods, and health, and may face displacement as mining expands. Government agencies are also key stakeholders, as they are responsible for issuing permits, enforcing environmental regulations, and determining whether mining can occur in protected or Indigenous territories.

This project will analyze mining-related deforestation within a defined region and time period, examining how proximity to infrastructure and land-use designations influence forest loss. By narrowing the scope to a specific geographic area and dataset, the project is feasible within a two-month timeframe.

# Datasets

## Source 1:
USDA Research Data Archive: Dataset of gold-mining related deforestation and formalization in Madre de Dios, Perú from 2001 to 2014
([https://www.fs.usda.gov//rds/archive/catalog/RDS-2021-0083]())

## Link to Data: 
[https://www.fs.usda.gov/rds/archive/products/RDS-2021-0083/RDS-2021-0083.zip]()

## Variable:

**year** - Ordinal

**unq** - Nominal

**districtcode** — Nominal

**area_m2** - Continuous 

**disttonavriv** - Continuous 

**com_nativa** - Binary


## Source 2:

Global mining deforestation footprint data from 2000 to 2019

### Link to Data:
[https://zenodo.org/records/7307210/files/global_mining_forest_loss.csv?download=1]()

### Variable:
**id** — Nominal identifier; categorical

**id_hcluster** — Nominal (cluster/group ID; categorical, no order)

**list_of_commodities** — Nominal (multi-label) 

**isoa3** — Nominal 

**country** — Nominal 

**ecoregion** — Nominal 

**biome** — Nominal

**year** — ordinal

**area_forest_loss_XXX_YYY** — Ratio (continuous)


## Source 3:
Global Forest Watch dashboard
([https://www.globalforestwatch.org/dashboards/global/]())

### Link to Data:

[https://gfw2-data.s3.amazonaws.com/country-pages/country_stats/download/2024/global_05212025.xlsx]()

### Variable:

#### Subnational 1 Drivers

**country** - Nominal

**subnational1** - Nominal

**threshold** - Discrete

**driver** - Nominal

**year** - Continuous

**tc_loss_ha** - Continuous

#### Subnational 1 Primary Loss

**country** - Nominal

**subnational1** - Nominal

**threshold** - Discrete

**tc_loss_ha_2002**- Discrete

*(tc_loss_ha_2002 through tc_loss_ha_2024 all contain discrete values)*

