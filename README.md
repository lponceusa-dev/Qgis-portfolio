# Qgis-portfolio
Recent Graduate from Binghamton University. Building spatial analysis skills through real QGIS projects. Including flood risk, land use change, transit equity. Working with USGS, FEMA, and Census datasets. Interested in environmental risk and urban planning. Open to GIS project work and collaborations.

# Geospatial Analysis Portfolio 
A collection of self-directed GIS projects built in QGIS 3.34 LTR, applying core spatial analysis workflows to real-world problems using publicly available federal datasets. Each project covers the full pipeline — data acquisition, processing, analysis, and cartographic output.
# Projects
Urban Flood Risk Assessment — Harris County, TX

Multi-layer flood vulnerability analysis combining SRTM elevation data (USGS), FEMA National Flood Hazard Layer, and US Census population data. Uses raster calculation to identify low-elevation flood-prone zones (≤8m), intersects those zones with census tracts, and generates a composite 0–1 vulnerability index weighted by physical exposure (60%) and population density (40%). Final map validated against Hurricane Harvey (2017) inundation extents. Tools: GDAL, Raster Calculator, Polygonize, Spatial Join, Field Calculator, Graduated Symbology, Print Layout. CRS: EPSG:32615.
Land Use / Land Cover Change Detection — Binghamton, NY

Multi-temporal raster analysis comparing NLCD classifications from 2011 and 2021 to quantify urban sprawl and green space loss across Broome County. Produces a class-transition change matrix and choropleth map using EPSG:5070 (Albers Equal Area). Tools: Reclassify by Layer, Raster Calculator, Zonal Statistics.
Transit Accessibility & Equity Analysis — Broome County, NY

Network-based walking catchment analysis from GTFS bus stop coordinates using QNEAT3 service area tools. Intersected with ACS low-income population data to surface transit deserts — areas of high need and poor coverage. Output: bivariate choropleth map. Tools: QNEAT3, Join by Location, OSM road network.
Data Sources

USGS EarthExplorer · FEMA Map Service Center · US Census TIGER/ACS · USGS NLCD · OpenStreetMap · GTFS (BC Transit)
Stack

QGIS 3.34 LTR · GDAL · Processing Toolbox · QuickOSM · QNEAT3
About

# About me 
I'm a former student from Binghamton University building hands-on GIS skills through project-based work. Interested in environmental risk, urban equity, and the role spatial data plays in real planning decisions. All datasets used are free and publicly available — workflows are fully reproducible.
