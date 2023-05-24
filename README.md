Project done as part of the course UEP238 (Data Science for Urban Sustainability), Spring 2023, Tufts University.

Collaborator: Patrali Ghosh

Abstract of the project:
<br>
Measuring air pollution has been a rising topic of interest among researchers as climate change is gaining popularity on a global scale. The exposure to air pollution changes based on one's mode of transportation. The method of transport significantly impacts a person's travel time and thus their exposure to air pollution. This paper focuses on pedestrians' exposure to air pollution in the Greater Boston Region. We found places in the center of Boston with high concentrations of NOx. Based on a literature review, we hypothesized that the places with high walkability index are the places where the exposure to air pollution is also high. In this paper, we performed multiple spatial regression analyses to find if there is any correlation between walkability and the variables  used to calculate it, and the concentration of NOx at a census block group level in the Greater Boston Region. We found evidence of a positive correlation between these two sets of variables.
<br>

Datasets used:

* Census 2010 Census Block Groups (CBGs) boundary shapefile provided by MassGIS<sup>1</sup> [(Download)](https://tufts.box.com/s/ae2qm0i44kk6a22rfp2o9k87he65m239).
* National Walkability Index dataset, part of Smart Location Mapping provided by the United States Environmental Protection Agency<sup>2</sup> [(Download)](https://tufts.box.com/s/dk4272w0wbiqj92fkdu3r7upc0407li1).
* NOx Concentration in ppb downloaded for Greater Boston Area (10m x 10m grids) from the C-LINE tool, jointly provided by Chapel Hill's Institute for the Environment and the United States Environmental Protection Agency<sup>3</sup> [(Download)](https://tufts.box.com/s/wd60ny5p1mrc9a4qoi2rd80m6zwax83g).
<br>

<sup>1</sup> [MassGIS Data: 2010 U.S. Census | Mass.gov](https://www.mass.gov/info-details/massgis-data-2010-us-census)
<br>
<sup>2</sup> [Smart Location Mapping | US EPA](https://www.epa.gov/smartgrowth/smart-location-mapping#SLD)
<br>
<sup>3</sup> [Community-LINE Source Model (C-LINE) to estimate roadway emissions | US EPA](https://www.epa.gov/healthresearch/community-line-source-model-c-line-estimate-roadway-emissions#:~:text=What%20is%20the%20Community%2DLINE,fleet%20mix%20and%20vehicle%20speed), This dataset was downloaded and provided by Hongkun Huang (Hongkun.Huang@tufts.edu)


