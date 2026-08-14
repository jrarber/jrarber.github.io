---
title: "Projects"
permalink: /projects/
author_profile: true
layout: single
---


## Southeast Swamp Delineation 
Swamps (in the broad sense) are forested wetlands, landscapes where flooding occurs often with varying degrees of intensity. Historically, foresters have delineated these different forest communities in a suggestive, haphazard manor. While this has worked for 100 years, we currently lack objective classifications of these communities overall. Typically classified as flatwoods, bottomlands, or swamps (strict sense); we lose a lot of fine-grain detail of distinct species associations. 



## Functional Diversity of Arkansas Floodplain Forests


## Ecological Radiation of the genus *Carya*
Hickories (*Carya spp.*) are an important genus across the eastern United States. 



## `arber` R package for forest, soil, and spatial ecology
This is mainly a group of functions that make my life easier. Primarily, `arber` builds on publicly available data, such as USFS Forest Inventory and Analysis, BioClim climate data, and soil characteristics (see below). Shapefiles of US regions, states, and EPA ecoregions are built in for quick reference and plotting. 

![Map of soil sand content in the American Southeast](/southeast_sand.png)

`arber` also includes functionality to build soil characteristic rasters from publicly available data ([polaris (Chaney et al. 2016)](http://hydrology.cee.duke.edu/POLARIS/); [Soil Landscapes of the US (SOLUS) (USDA 2024)](https://storage.googleapis.com/solus100pub/index.html)) to match US states or regions, such as the map above. The spatial aspect of merging these rasters is handled by `terra` on the backend. 
