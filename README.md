# nyc-muesums-map
Map of NYC museums and transportation

Tools Used
- ArcGIS Pro (Main - for mapping the  layers)
- Google Colab (Data Cleaning)

## Process:
- Data Cleaning (Python) (File name: clean_museum_price.py and clean_museum_nyc.py)
  - Focusing on Museums in Manhattan
  - Removing museums that are closed/temporarily closed
-  Visualizing using ArcGIS Pro

## Map (From bottom to top layers)
1. Basemap: Newspaper (ArcGIS Basemap)
2. Parks
3. Subway Lines
4. Museum Buffer (0.2 - walkable distance to subway stations)
5. Gallery (Clusters)
6. Museums (Clusters)
7. Neighborhoods (NYC Neighborhoods - i.e., Chinatown, Midtown, East Village,...)

## Symbology
- Museum:
  - Points:
    - Blue Tear Pin 
    - In/out beyond: None
  - Clusters:
    - Blue Circle (same color as points)
    - Minimum size: 12
    - Maximum size: 70
    - In/out beyond: None
  - Buffers
    - Transparent Circles with Blue Outlines
    - Out Beyond: 3,953
      >Only appears when users zoom in closer to the map and are able to see individual Museum Points
- Subway stations: Train icon
  - Out Beyond: 1:50,000 (Too many subway stations -> Less important than museum points -> Overcrowds the map -> Set Out beyond)
- Subway Lines: Lines
  - Colors based on the NYC MTA system (https://www.mta.info/map/5256)
  - Grouping individual segments into groups by colors: 
- Gallery Points: TBD
- Parks:
  - Green Fill
  - Out beyond: 89 892
- Neighborhood and foot traffic count: TBD

## Labeling
