---
layout: page
title: ArcGIS Embedded Map
---

# Student Poverty & Missing Youth Map

<!-- Load ArcGIS Embeddable Components -->
<script type="module" src="https://js.arcgis.com/embeddable-components/4.33/arcgis-embeddable-components.esm.js"></script>

This interactive map uses Census data on school-enrolled children aged 3 and above to visualize poverty rates across San Diego County.  
It overlays these trends with the locations of missing youth (ages 13–17), revealing a strong spatial correlation in many census tracts.

<div style="width: 100%; max-width: 900px; height: 600px; margin-top: 20px; border: 1px solid #ccc;">
  <arcgis-embedded-map 
    style="width: 100%; height: 100%;" 
    item-id="ec23b7371be647968689a93c200de8e7" 
    theme="light" 
    center="-117.02850659779222,32.74568780765893" 
    scale="288895.2771445" 
    portal-url="https://sdsugeo.maps.arcgis.com">
  </arcgis-embedded-map>
</div>

