---
layout: archive
title: "Geospatial Projects"
permalink: /GIS/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<h2>Side Lot Sales Policy</h2>
This analysis was to determine which parcels were eligible for the side lot sales policy based on 3 conditions. (1) The property has to be available within the database, (2) its area has to be <4,000 sq feet and (3) not spatially contiguous to another property. 
The below images identifies the first two conditions via the hatched symbol. To determine eligibility for contiguity, a buffer of a buffer was used to de-select parcels. See the below (right) image.
<div>
<img src='/images/sidelot1.png' style='height:300px'> 
<img src='/images/sidelot2.png' style='height:300px'> 
</div>
Because data is not always consistent, there are issues with this analyses where eligible side lots are not identified because of the 'T' shape (left) and diagonal parcels (right).
<div>
<img src='/images/sidelot3.png' style='height:300px'> 
<img src='/images/sidelot4.png' style='height:300px'> 
</div>
This workflow below needs to be modified to correct for these errors. 
<img src='/images/sidelot5.jpg' style='height:200px'> 


<h2>ARPA Transparency Portal</h2>
This [interactive dashboard](https://insights.arcgis.com/#/view/2f02aea33af84a8381c78d4de648f67c) was created through ArcGIS Insights. It serves as the transparency portal for appropriations, programmed funds and expenditures as it relates to the American Rescue Plan Act projects. <br>
<img src='/images/arpa.png'> <br> 

<h2>Community Benefits Scorecard</h2>
This [Community Benefit Scorecard](https://experience.arcgis.com/experience/59fdb098b25146bca7063802e1bb3c2a/page/Residential/?draft=true) was created to inform the Economic Development Incentives team about how each potenial project scored against the pre-determined variables and depending on which category they fall under- Residential, Commercial or Mixed Use. The variables considered while creating the score are transit access, whether or not it is a vacant building, its location etc. There is a maximum number of points available for each of these variables. <br>
The data behind this scorecard was queried using SQL, and automated using Python and windows task scheduler.  <br>
<img src='/images/communityscorecard.png'> <br> 
<br> 

**In addition to these public facing ones, I also created internal facing dashboards and applications and conducted appropriate geospatial analyses**

<h2>GeoVisualization Examples</h2>
The below image shows 3 maps with the same theme (Global Fires), and different purposes to highlight the relationship between month-long fires (~70,000 records), landcover type and other variables.
<img src='/images/final-project-C&GV-Gizelle.png' style='height:400px'> 

The below image compares NDVI values to Species Richness values broken down by year and highlighting the drought severity and coverage index (DSCI). This analysis and image was generated using python.
<img src='/images/DroughtStrees vs NDVI vs SpeciesRichness v3.png' style='height:300px'> 

The below 2 images are based on my thesis, highlighting the change in land cover over time. Each image shows a unique way of presenting the changes in land cover. 

<img src='/images/1_LandCover_in2019_that_was_evergreen_forest_in_2010_2.png' style='height:300px'> 
<img src='/images/2_residential_land_cover_changefrom2010to2019.png' style='height:300px'> 

To read more about the research please visit the [Remote Sensing](https://cotag11.github.io/RemoteSensing/) page. 

<h2>Surveys</h2>
The below 'Data Collection Survey' was created using desktop interface for ArcGIS Survey123. It is able to create two tables having a one-to-many relationship between them based on the inputs from the survey.  
<div>
<img src='/images/survey_1_data_collection_details.png' style='height:500px'> 
<img src='/images/survey_2_data_collection_details_flight_details_2.png' style='height:500px'> 
</div>


<br>
*last updated in 2024
