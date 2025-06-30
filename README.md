# REFERENCE DATA COLLECTION FOR IMPROVING LAND USE CHANGE MAPPING IN GHANA
This repository hosts reference datasets developed by **CERSGIS** with support from the **Lacuna Fund, GIZ, WRI,** and other local partners. This was necessary to address critical gaps in monitoring deforestation drivers like cocoa farming and illegal gold mining (Galamsey) across six (6) regions and 15 districts in the southern zone of Ghana.
The project provides open, high-quality geospatial reference data to support land use and land cover (LULC) mapping, climate monitoring, sustainable agriculture, and forest conservation, especially within the cocoa-forest mosaic landscape.

### The dataset combines:
- 20,035 reference point samples for Galamsey, oil palm, rubber, and open/degraded forest, collected for land use and land cover mapping in Ghana’s cocoa-forest mosaic regions.
- 21,141 reference cocoa farm polygons with detailed attributes (e.g., shade trees, farm size).
- 14,331 homogenous reference cocoa farm polygons with detailed attributes.
- 4,444 anonymized socioeconomic surveys.

## Key Features
- 21,141 mapped cocoa farm polygons with rich attributes (e.g., shade tree presence, farm size).
- 14,331 homogenous cocoa field polygons for improved training of machine learning models.
- 20,035 reference point samples covering Galamsey sites, oil palm and rubber plantations, and degraded/open forest.
- 4,444 anonymized household-level socioeconomic surveys linked to land use patterns.
- Focused on six cocoa Hotspot Intervention Areas (HIAs) under Ghana’s Cocoa Forest REDD+ Programme.
- Developed to improve land cover classification in complex tropical mosaics, where cocoa is often misclassified as natural forest.


## Methodology
The project employed a three-phase approach:

1. Training and Capacity Building
   - CERSGIS, in collaboration with SERVIR and Boston University, conducted a training-of-trainers workshop.
   - 30+ university students and local youth were trained in satellite image interpretation and field data collection.
   - Tools used included Collect Earth Online, Ground App, and GPS-based field mapping.
  
2. Satellite Image Analysis
   - Used Planet monthly mosaics to interpret land cover in the cocoa-forest mosaic.
   - Focused on identifying cocoa, Galamsey, oil palm, rubber, and other agriculture.
   - Implemented consensus labeling and quality control across annotators.
   - Mapped areas of uncertainty to guide targeted ground truthing.
  
3. Field Data Collection
   - Collected detailed ground data on cocoa farms and surrounding land uses.
   - Recorded polygon boundaries and attributes such as tree shade, crop type, and management practices.
   - Mapped additional land use features (e.g., Galamsey, oil palm, degraded forests) using GPS points.
   - Administered household surveys on livelihoods, land tenure, and community perceptions of land use change.


## Tools
- **Google Earth Engine** – for remote sensing analysis and visualization
- **Collect Earth Online** – satellite image interpretation
- **Ground App** – custom mobile field data collection
- **Python/Pandas/GeoPandas** – data wrangling and preprocessing
- **QGIS/ArcGIS** – spatial data cleaning, processing and spatial data management


## Possible Uses
This dataset is openly accessible to support:
- **Machine learning** and AI-based land use classification.
- **Monitoring deforestation drivers** like cocoa expansion and illegal mining.
- **Forest carbon accounting** and climate change mitigation strategies.
- **Development of LULC basemaps** and annual change detection models.
- **Socio-ecological analysis** linking livelihoods with land transformation.
- **Policy planning** under REDD+ and sustainable cocoa initiatives.
- Academic **research**, capacity building, and tool development.


## Data Access
All data provided in this repository is openly available and organized into:
- Cocoa_Field_Polygons/ – Shapefiles of cocoa farm boundaries with attributes.
- Other_LULC_Points/ – Reference point shapefiles for Galamsey, oil palm, rubber, etc.
- Socioeconomic_Surveys/ – Anonymized CSV datasets with household-level information.
- Documentation/ – Survey forms, attribute guides, metadata, and methodology notes.


## Keywords
Ghana, cocoa deforestation, Galamsey, remote sensing, land use land cover classification, machine learning


## Contact
For questions, collaboration, or feedback, please contact:
### CERSGIS (Centre for Remote Sensing and Geographic Information Services)
📧 <a href="mailto:info@cersgis.org">info@cersgis.org</a>
🌐 <a herf="www.cersgis.org">www.cersgis.org</a>