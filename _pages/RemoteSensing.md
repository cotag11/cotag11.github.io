---
layout: archive
title: "Remote Sensing Projects"
permalink: /RemoteSensing/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<h2>Forest Conservation with Deep Learning</h2>
This research involved creating a land use land cover map for Betampona Nature Reserve in Madagascar. The objectives were to develop an end-to-end mapping of the tropical forest using fully convolution neural networks (FCNNs) using WorldView-3 (WV-3) imagery and secondly to quanify the human impact on the environment. The FCNN (U-Net) model which used spatial/textural information was compared with pixel-based methods including Support Vector Machine (SVM), Random Forest (RF), and Deep Neural Network (DNN). Spatiotemporal analysis was also conducted using the results of this research and a previously generated land use land cover map. This analysis showed a 0.7% increase in Evergreen Forest within the BNR and a 32% increase in tree cover within residential areas likely due to forest regeneration and conservation efforts. <br>
[Click here](https://www.mdpi.com/2072-4292/13/17/3495) to read more about the research. <br>
<div>
<img src='/images/graphical.png' style='height:300px'> 
<img src='/images/change.png' style='height:300px'> 
</div>

<h2>Missouri as Art</h2>
Similar to the [Earth as Art](https://eros.usgs.gov/media-gallery/earth-as-art) image collection, the below images were created for various locations in Missouri. 
<br>The below False Color Images (FCC) are created by displaying any bands other than the Red, Green and Blue in the respective red, green and blue channels of the computer. By displaying bands other than the visible, we can see the unseen. False Color images are used to highlight certain features; for example, the combination (NIR, R, G) highlights vegetation in shades of red. 
<head><style>
        table {width: 100%; border-collapse: collapse; border: none;/* Ensures no double borders */ }
        th, td {padding: 8px; text-align: center; border: none; /* Removes the borders from cells */}
        img {max-width: 300px; height: auto;}</style> </head>
<body><table><tr><td><img src='/images/johnson.png' style="width: 500px; height: auto; margin-right: 10px;"> </td>
        <td><img src='/images/geometric.png' style="width: 500px; height: auto; margin-right: 10px;"> </td>
        <td><img src='/images/stl.png' style="width: 500px; height: auto; margin-right: 10px;"> </td>
    </tr>
    <tr>
<td>This band combination highlights undulating terrain in south-eastern Missouri. Vegetation is seen in green because of the high reflectance in NIR (Near Infrared), exposed rocks are colored red due to SWIR 2 (Shortwave Infrared) bands. Finally, exposed sediments are in shades of pink due to SWIR 2 and Red Edge 1. 
<br>Sentinel-2: SWIR 2, NIR, Red Edge 1 (B12, B8, B5)
<br>Date Acquired: October 22nd, 2015
</td>
<td>This band combination highlights patterns observed in a residential cul-de-sac in O’Fallon, Saint Charles county. The paved roads and concrete structures have a high reflectance in Red and Red Edge 2 resulting in the orange color. Vegetation has a high reflectance in the NIR (Near Infrared) and thus appears in shades of blue. 
<br>Sentinel-2: Red, Red Edge 2, NIR (B4, B6, B8)
<br>Date Acquired: May 20th, 2016
</td>
<td>These images are created using a single band. A color scheme is used to display the at-surface brightness temperature, created using TIR1 band (band 10). St Louis city is hotter while the clouds are at lower temperatures. The image shows the clouds created using the cirrus band. Even thinner clouds can be seen through this band, not possible with any image visualizations. 
</td></tr></table></body>

(Click here)[https://github.com/MissouriView/Missouri-as-Art] to view more images created as part of this series. 
