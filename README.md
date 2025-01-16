# AGILE 2025 - Call for Papers
**Call for papers for the 28th AGILE conference, Geographic Information Science responding to Global Challenges, Dresden, Germany on 10-13 June 2025**

The Association of Geographic Information Laboratories in Europe (AGILE) has held annual conferences focused on Geographic Information Science since 1998. The next AGILE 2025 conference will be held in Dresden, Germany, on 10-13 June 2025.

The conference theme “Geographic Information Science responding to Global Challenges” recognizes the pivotal role of geospatial data and analysis in informing decision-making for current global issues affecting humanity, the environment, and global resilience ([more information about AGILE 2025](https://agile-gi.eu/conference-2025/call-for-papers-2025).

# Centrality and Resilience in the Face of Flooding: A Case Study of Rio Grande do Sul

The topic of this study includes _Open Spatial Data, Open Science, Open-source Geospatial Tools and Applications_ , _Disaster and Risk Management_, _Way Finding, Routing and Indoor Navigation_ or _Spatial Databases and Data Management_. 

We used open-ssource data and software including OpenRouteService (ORS),Pgrouting, PostGIS, R or QGIS. In addition, we mainly used the open-source data from OpenStreetMap (OSM). Based on centrality metrics and alternative paths, we compared the centrality of the road network in the core of the metropolitan area of Rio Grande do Sul before and after the flood event that took place on the 29th of April of 2024. The methodology is mainly conducted in SQL using PostGIS to handle geospatial data and Pgrouting to analyze road networks.

The submission type is _use case_.

# Overview

```
project
|- doc/            # documentation for AGILE 2025 full paper
|  +- paper/       # manuscript(s)
|
|- data            	            
|  |- source_data/  		      # raw data
|  |- results_data/ 		      # final data
|    + - select_area_of_interest/
|    + - obtain_routable_networks/
|    + - analyse_centrality_and_resilience
|  |- temp_data/                      # temp data  	
|- code/                           
|  |- paper/                          # Reproducible paper using Quarto includes code
|  | + quarto_script_rs_paper_v0.Rmd  # Quarto file
|  |- figures/                        # diagrams, images, and other non-graph graphics
|
|- README                             # the top level description of content
```


## Datasets
- [x] Is provided in a non-propietary format:

This github repository contains the data in non-propietary format. Spreadsheets are in ".csv" format, geospatial data in geopackage.  

- [x] Is documented for third parties to reuse:

Is accessible in a public repository and has an open data licence:
- [x] The github and zenodo repository are public and licensed under Creative Commons Attribution 4.0 International Public License.

## Software tools libraries packages and computational workflows

Pending to acceptance of the full paper submission on the 27th of February according to [AGILE 2025 call for papers](https://agile-gi.eu/conference-2025/call-for-papers-2025), we will include additional documentation.
- [x] Reproduction steps are explained in a README (plain text file), flowchart, or script:

The quarto_script_rs_paper_v0.Rmd includes the flowchart and script to reproduce results of the paper.

- [x] Computational environements (including hardware) are documented or provided :
- [x] Versions of relevant software components (libraries, packages) are provided:
- [x] All parameters and expected execution times for the computational workflow are provided:

The section 2.4 Data and Software Availability Section includes this information. A detailed view of is provided after full paper acceptance.

- [x]  Software developed by the authors is available in a public repository and has an open licence:

The software OpenRouteService is available in the follwoing [public repository](https://github.com/GIScience/openrouteservice) (https://github.com/GIScience/openrouteservice)

- [x] There is a clear connection between tables, figures, maps, and statistical values and the data and code that they are based on, e.g., using file names or documentation in README:

Results are named according to the flowchart shown as Figure 2 in the section 2.1. Pre-processing.

# Contact
X (x@xxx.com)
# License
This project is licensed under Creative Commons Attribution 4.0 International Public License, see file LICENSE.
