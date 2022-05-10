# myctobase

This repository contains short code to transform raw data of dataset `Myctobase, a circumpolar database of mesopelagic fishes for new insights into deep pelagic prey fields - data`


## Dataset decription

The raw data is available at Zenodo:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6131579.svg)](https://doi.org/10.5281/zenodo.6131579)

Darwin Core formatted of this dataset is published in the portals below. 

portal | link
:-- | :--
IPT | 
GBIF | 
OBIS | 

## Repo structure

```
.
├── README.md 			: description of this repository
├── myctobase.Rproj	        : R Project
├── data			: directory to store data
│   └── processed		: directory to store processed data
├── html			: HTML of knitted Rmd files
│   └── transform-data.html	
├── renv 			: renv files for dependencies
├── renv.lock			: describe the state of project's library
└── src
│   └── transform-data.Rmd	       : Rmarkdown file of the code
```

Knitted Rmarkdown can be rendered at https://raw.githack.com/biodiversity-aq/myctobase/main/html/transform-data.html

## Getting started

If dependencies are not automatically installed by `renv` when you open `SO_isotopes.Rproj`, try the following command.

```{r}
renv::restore()
```
You can run chunks of R code in `transform-data.Rmd` or knit them into html.
