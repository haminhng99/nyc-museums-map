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
1. Basemap: Newspaper (ArcGIS Basemap)
2. Parks
3. Subway Lines
4. Museum Buffer (0.2 - walkable distance to subway stations)
5. Gallery (Clusters)
6. Museums (CLusters)
7. Neighborhoods (NYC Neighborhoods - i.e. Chinatown, Midtown, East Village,...)

Symbology
- All Museum points are turned to a cluster 

Labeling
