---
layout: archive
title: "Remote Sensing Projects"
permalink: /RemoteSensing/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<h2>Mapping Annual Deforestation in Madagascar</h2>
This research attempts to bridge that gap and compute annual forest cover change over time from 2015 to 2019 using an automated land cover mapping method. Land cover maps are most commonly created through the classification of remotely sensed images which can be easily computed on a cloud-based platform like GEE, Google Earth Engine. Availability of relevant imagery data on the platform itself and ability to analyze data allows for an automated and repeatable workflow. Spectral, and extracted features derived from Landsat 8 imagery, along with environmental variables (DEM, soil type) are used as inputs into the classification model. The generated classification maps were then compared to compute annual forest change.
<div>
<img src='/images/land cover 2019.png' style='height:300px'> 
<img src='/images/forest cover 2019.png' style='height:300px'> 
</div>

<h2>Forest Conservation with Deep Learning</h2>
This research involved creating a land use land cover map for Betampona Nature Reserve in Madagascar. The objectives were to develop an end-to-end mapping of the tropical forest using fully convolution neural networks (FCNNs) using WorldView-3 (WV-3) imagery and secondly to quanify the human impact on the environment. The FCNN (U-Net) model which used spatial/textural information was compared with pixel-based methods including Support Vector Machine (SVM), Random Forest (RF), and Deep Neural Network (DNN). Spatiotemporal analysis was also conducted using the results of this research and a previously generated land use land cover map. This analysis showed a 0.7% increase in Evergreen Forest within the BNR and a 32% increase in tree cover within residential areas likely due to forest regeneration and conservation efforts. <br>
Read the [published research](https://www.mdpi.com/2072-4292/13/17/3495) or interact with the [Story Map](https://storymaps.arcgis.com/stories/1d494c409f1e4ee99dc7133d27ab957a) to learn more. <br>
<div>
<img src='/images/graphical.png' style='height:300px'> 
<img src='/images/lulc.webp' style='height:300px'> 
<img src='/images/invasive.webp' style='height:300px'> 
</div>

<h2>Missouri as Art</h2>
Similar to the [Earth as Art](https://eros.usgs.gov/media-gallery/earth-as-art) image collection, the below images were created for various locations in Missouri. 
<br>The below False Color Images (FCC) are created by displaying any bands other than the Red, Green and Blue in the respective red, green and blue channels of the computer. By displaying bands other than the visible, we can see the unseen. False Color images are used to highlight certain features; for example, the combination (NIR, R, G) highlights vegetation in shades of red. <br>
     
     
<head>
   <style>
        .image-container {
            display: flex;
            justify-content: space-around;
          flex-wrap: wrap; /* Allows images to wrap if necessary */
        }
        .image-item {
            text-align: center;
          flex: 1;
            max-width: 33%; /* Ensure that each image-item takes up one-third of the container width */
            box-sizing: border-box;
            padding: 10px; /* Adds space around each image-item */
        }
        .image-item img {
            max-width: 100%;
            height: 300px; 
        }
        .image-item p {
            margin: 0;
            padding: 5px;
        }
    </style>

</head>
<body>
<div class="image-container">
        <div class="image-item">
           <img src='/images/johnson.png' style="width: 500px; height: auto; margin-right: 10px;"> 
           <p>This band combination highlights undulating terrain in south-eastern Missouri. Vegetation is seen in green because of the high reflectance in NIR (Near Infrared), exposed rocks are colored red due to SWIR 2 (Shortwave Infrared) bands. Finally, exposed sediments are in shades of pink due to SWIR 2 and Red Edge 1. 
<br>Sentinel-2: SWIR 2, NIR, Red Edge 1 (B12, B8, B5)
<br>Date Acquired: October 22nd, 2015</p>
        </div> <div class="image-item">
        <img src='/images/geometric.png' style="width: 500px; height: auto; margin-right: 10px;"> 
          <p>This band combination highlights patterns observed in a residential cul-de-sac in O’Fallon, Saint Charles county. The paved roads and concrete structures have a high reflectance in Red and Red Edge 2 resulting in the orange color. Vegetation has a high reflectance in the NIR (Near Infrared) and thus appears in shades of blue. 
<br>Sentinel-2: Red, Red Edge 2, NIR (B4, B6, B8)
<br>Date Acquired: May 20th, 2016</p>
        </div>
        <div class="image-item">
       <img src='/images/stl.png' style="width: 500px; height: auto; margin-right: 10px;"> 
<p>This image is not a false color composite, as it was created using a single TIR1 band (band 10) from Sentinel-2 data. A color scheme is used to display the at-surface brightness temperature. The urban concrete areas in the city have a higher surface temperature, while Forest Park and other larger parks have a comparatively lower tempwerature, a good visualization of the importance of green spaces in our urban environments. This image also captured the cooler clouds. </p>
        </div>
    </div>
</body>
To see more images created as part of this series, [click here](https://github.com/MissouriView/Missouri-as-Art/). 
<br>
<br>
*last updated in 2024
