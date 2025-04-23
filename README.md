# nyc-muesums-map
Map of NYC museums and transportation

Tools Used
- ArcGIS Pro (Main - for mapping the  layers)
- Google Colab (Data Cleaning)

Process:
- Data Cleaning (Python) (File name: clean_museum_price.py and clean_museum_nyc.py)
  - Focusing on Museums in Manhattan
  - Removing museums that are closed/temporarily closed
-  Visualizing using ArcGIS Pro

Map (From bottom to top layers)
- Basemap: Newspaper (ArcGIS Basemap)
- Parks
- Subway Lines
- Museum Buffer (0.2 - walkable distance to subway stations)
- Gallery (Clusters)
- Museums (CLusters)
- Neighborhoods (NYC Neighborhoods - i.e. Chinatown, Midtown, East Village,...)

Symbology
- 
