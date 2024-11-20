# Potential Marine Aquaculture

A geospatial analysis project focused on identifying suitable marine aquaculture areas along the U.S. West Coast based on environmental constraints.

## Description

This project uses marine organisms' optimal depth and water temperature to explore chances of marine aquaculture along the Western United States. Areas along the coast that hold these optimal conditions are identified and mapped. The two species seen in this example are oysters and red abalone, however the parameters can easily be changed to account for any species of choice. Each exclusive economic zone has their potential aquaculture area tallied and mapped, so we can visualize which zone may be the best to pursue aquaculture of that species.

## Getting Started

### Dependencies

Ensure you have the following prerequisites installed:

R (version 4.0 or later)   

R packages: terra, sf, tidyverse, tmap, testthat, kableExtra

Quarto for rendering reports

Operating System: macOS, Linux, or Windows 10+

### Installing

Clone the repository from GitHub Classrooms:

https://github.com/efairbanks000/potential-marine-aquaculture.git

Your repository structure should look like this:

```
potential-marine-aquaculture
│   README.md 
│   analysis.qmd 
│   .gitignore 
│
└───data  
    │   wc_regions_clean.shp 
    │   depth.tif 
    │   average_annual_sst_2008.tif 
    │   average_annual_sst_2009.tif 
    │   average_annual_sst_2010.tif 
    │   average_annual_sst_2011.tif 
    │   average_annual_sst_2012.tif
```


## Authors

Eric Fairbanks

efairbanks@ucsb.edu

## Acknowledgments

I want to thank Ruth Oliver, Ale Vidal Meza, and my EDS 223 peers who helped with data accessibility, inspiration, and troubleshooting issues.
