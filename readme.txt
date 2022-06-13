Readme for the CaPTrends dataset

Contact Thomas.frederick.johnson(at)outlook.com with any queries

CaPTrends is a dataset describing abundance/density changes in four families of the order Carnivora: Canidae, Felidae, Hyaenidae and Ursine

CaPTrends is relational in nature, not just within itself, but across the data landscape

captrends.csv contains all master data, including the taxnomic, temporal, and spatial information, as well as the trend type and magnitude, and raises any potential data issues with a series of indicators. captrends.csv can also be linked to: 

1) abundance.csv links through the ‘DataTableID’ field. abundance.csv contains abundance estimates through time for trends with a “Quantiative_method” of Manual calculation required.

2) direction.csv links through the ‘DataTableID’ field. direction.csv describes the presence of threats and conservation actions present in each population trend.

3) source.csv links through ‘Citation_key’. source.csv indicates which references from the systematic search contained population trend data.

The metadata for each file is presented within this repository, and we also provide the amended phylogeny used in the CaPTrends manuscript, which corrects for differences between the Upham et al., (2019) mammal phylogeny and the IUCN taxonomy. A full description of these “corrections” are described in the CaPTrends supplementary material: Using the IUCN taxonomy with a phylogeny.

Further details describing how CaPTrends was developed are available in the published manuscript.

References:

Upham NS, Esselstyn JA, Jetz W (2019) Inferring the mammal tree: Species-level sets of phylogenies for questions in ecology, evolution, and conservation. PLoS Biol 17(12): e3000494. https://doi.org/10.1371/journal.pbio.3000494
