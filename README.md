## Citation:
Petracca LP, SJ Converse, BT Maletzke, and B Garner. In review. Forecasting dynamics of a recolonizing wolf population under different management strategies.

## Abstract:
Species recovery can be influenced by a wide variety of factors, such that predicting the spatiotemporal dynamics of recovering species can be exceedingly difficult. These predictions, however, are valuable for decision makers tasked with managing species and determining their legal status. We applied a spatially explicit projection model to estimate population growth and viability of gray wolves (Canis lupus) from 2021-2070 in Washington State, USA, where wolves have been naturally recolonizing since the establishment of the first resident pack in 2008. Using this model, we predicted the effects of 12 scenarios relating to management actions (e.g., lethal removals by the state agency, translocation, recreational harvest) and system uncertainties (e.g., immigration from out of state, disease) on the probability of meeting Washington’s wolf recovery goals, the probability of extinction, and other metrics related to population status. Population recovery was defined under Washington’s Wolf Conservation and Management Plan as four breeding pairs in each of three recovery regions and three additional breeding pairs anywhere in the state. The baseline and translocation scenarios indicated a high (>60%) probability of wolf recovery in Washington across all years (2021-2070), but scenarios related to harvest mortality (removal of 5% of the population every six months), increased lethal removals (removal of 30% of the population across the state every four years), and cessation of immigration from out of state resulted in low probabilities (0.02, 0.03, and 0.08, respectively) of meeting recovery goals across all years. All but two scenarios involving recreational harvest or lethal removals by the state agency resulted in a geometric mean of population growth  ≥1, indicating long-term population stability or growth depending on the scenario. Our results suggest that wolves will continue to recolonize Washington and that recovery goals will be met so long as harvest and lethal removals are not at unsustainable levels and adjacent populations support immigration into Washington.

## Code 
1) [Scripts](./scripts/): The main folder (described [here](./scripts/a_DESCRIPTION.txt)) contains 12 codes, one for each scenario for the projection model (2020-2070).

2) [Functions](./functions/): The main folder (described [here](./functions/a_DESCRIPTION.txt)) contains all functions related to the individual-based movement model. These functions allow for attraction of lone wolves, lethal removals, and dispersal of wolves depending on chosen territory selection method. 

## Data
Data files used to run the models in this paper are found in the [data](./data) folder. Please see [here](./data/a_DESCRIPTION.txt) for more information.