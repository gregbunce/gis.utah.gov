---
author:
  display_name: Bert Granberg
  email: agrc@utah.gov
date: 2011-11-03 18:11:05 -0600
title: SGID Base Map and Imagery Services
categories:
  - Developer
tags:
  - imagery
---
[![discover logo]({% link discover/images/discover-logo.png %}){: .flex .flex--center}]({% link discover/index.html %})

Do you need a quick base map for your [GIS, CAD, or web services]({% link discover/index.html %}#connect)? AGRC provides several multiscale base map and imagery service options that deliver prerendered base map tiles to your platform as fast as your internet connection will allow.

<div class="grid">
  <div class="grid__col grid__col--1-of-3 text-center">
      <h5 class="text-center">Imagery plus overlay</h5>
      <img src="{% link images/stgeorge_hybrid_basemap.png %}" class="outline">
  </div>
  <div class="grid__col grid__col--1-of-3 text-center">
      <h5 class="text-center">Terrain</h5>
      <img src="{% link images/brianhead_terrain_basemap.png %}" class="outline">
  </div>
  <div class="grid__col grid__col--1-of-3 text-center">
      <h5 class="text-center">Lite</h5>
      <img src="{% link images/provo_lite_basemap.png %}" class="outline">
  </div>
</div>
<i class="fas fa-exclamation-triangle"></i> **If you want to use the AGRC base maps, you'll need to have a [free account]({% link discover/index.html %}#services) and a quad word key created for you**. <i class="fas fa-exclamation-triangle"></i>
{: .pop .text-center }

AGRC’s cloud-based server, [Discover]({% link discover/index.html %}), provides imagery and base map services in an OGC standard WMTS and WMS in the Web Mercator WGS84 projection (wkid: 3857). Discover offers over [20 services]({% link discover/index.html %}#services) that are free to use (**but a few services do require a [signed license agreement]({% link discover/license/index.md %}))**.

<i class="fas fa-fw fa-info-circle"></i> Each cache consists of around **3 to 17 million** 256-pixel square tiles ranging from **15G to over 200GB**. These caches are standardized on a subset of the Google, Microsoft, and esri [scale levels]({% link developer/base-maps/basemap-scales/index.md %}) that apply to our state. The [update schedule]({% link developer/base-maps/basemap-maintenance-schedule/index.md %}) will keep you in the loop as to when the tiles were last updated. If you would like to download imagery, visit the [aerial photography]({% link data/aerial-photography/index.html %}) data page.

#### The Services on Discover

<i class="fas fa-fw fa-map"></i> **Terrain**: This base map highlights elevation and features mountain peak elevation labels, contour lines, and locations of ski resort locations and other places of interest.

<i class="fas fa-fw fa-map"></i> AGRC maintains a very minimal cache called **Lite**. It is very muted in color and does not distract from data overlaid on top of it.

<i class="fas fa-fw fa-map"></i> Up next is the **Imagery** base map. This tile set shows the Google aerial photography. For licensing reasons, you will need to qualify for an [organizational account login]({% link discover/license/index.md %}) to use to this base map.

<i class="fas fa-fw fa-map"></i> An exciting offering (_that we call squiggles and dots internally_) is a service called **Overlay**. This is a transparent set of tiles that displays styled roads and place-names. This can be overlaid on data for reference. Combining this with **Imagery** can create a desired **Hybrid** effect.

<i class="fas fa-fw fa-map"></i> We have the **Color Infrared**, **Address Points**, and **Topo** caches. The Color Infrared is a neat way to look at vegetation, while the Topo cache contains all of the USGS Quad Sheets. The Topo cache displays the most relevant quad sheet (i.e., 250K, 100K, or 24K) depending on your scale. The Address Points cache is a fast way to view around 2.5 million address points.

<i class="fas fa-fw fa-map"></i> There is also historical NAIP and Google imagery.


*[OGC]: Open Geospatial Consortium
*[WMTS]: Web Map Tile Service
*[WMS]: Web Map Service
*[NAIP]: National Agricultural Imagery Program
