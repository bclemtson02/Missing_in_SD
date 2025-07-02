---
layout: default
title: ArcGIS Embedded Map
---

# Student Poverty & Missing Youth Map

<!-- Load ArcGIS Embeddable Components -->
<script type="module" src="https://js.arcgis.com/embeddable-components/4.33/arcgis-embeddable-components.esm.js"></script>

This map overlays two datasets: Student poverty levels by school enrollment (shown in shades from yellow to dark blue, where darker blue represents higher levels of poverty)  and Missing youth aged 13-17 (represented by red triangles, with larger triangles indicating a higher count of missing teens).

The largest red triangles, indicating neighborhoods with the highest numbers of missing teens, appear in central areas like Kearny Mesa, Downtown, Encanto overlapping with darker blue census tracts that show higher levels of student poverty.

Similarly, several clusters in South County, including parts of San Ysidro and Otay Mesa, also show this overlap. Outlying areas with lighter colors (lower student poverty) generally have smaller or no red markers, indicating fewer missing youth cases.

Combining these two layers highlights a concerning spatial pattern: neighborhoods with higher rates of student poverty often coincide with areas reporting more missing teenagers. This suggests that economic hardship may be a factor contributing to youth vulnerability, possibly tied to instability at home, lack of resources, or increased exposure to exploitation.

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

