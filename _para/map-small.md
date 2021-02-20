---
title: Map (small)
permalink: /para/map-small.html
layout: para
map-on: true
---

## Small Map

```{% raw %}{% include feature/map-small.html mapid="first" filter="item.location contains '535 Outcropping'" zoom="16" latitude="48.950421" longitude="-117.016485" basemap="Esri_WorldImagery" %}{% endraw %} ```

{% include feature/map-small.html  filter="item.location contains '535 Outcropping'" zoom="16" latitude="48.950421" longitude="-117.016485" basemap="Esri_WorldImagery" %}

### Options:

- "filter" = logic statement (in liquid) that filters out most of the collection to display only select items. 
- "mapid" = short phase/name/id to disinguish map (esp. important if there are more than one map)
- "zoom" = how close (higher number) or far out (lower number) a level the map loads
- "latitude" = The coordinate at which you'd like map centered
- "longitude" = The coordinate at which you'd like map centered
- "basemap" = you can choose the layer of tiles you'd like Right now your options are: 
    - Stamen_Terrain,
    - OpenTopoMap,
    - Esri_WorldTerrain,
    - Esri_WorldStreetMap,
    - Esri_NatGeoWorldMap,
    - Esri_WorldImagery
