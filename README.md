# Nigeria Population Distribution Mapping

## Project Overview

This project visualizes population distribution across the 36 states of Nigeria and the Federal Capital Territory using QGIS and WorldPop population data.

The goal is to produce a clear thematic map showing differences in estimated population among Nigeria's states.

## Objectives

- Obtain administrative boundary data for Nigeria.
- Obtain state-level population estimates.
- Join population data to state boundaries.
- Create a graduated-color population distribution map.
- Design and export a professional cartographic layout.
- Document the GIS workflow using Git and GitHub.

## Tools and Technologies

- QGIS
- Git
- GitHub
- Visual Studio Code
- GeoJSON
- GeoPackage
- WorldPop population data

## Data Sources

### Administrative Boundaries

- **Source:** geoBoundaries
- **Country:** Nigeria
- **Administrative level:** ADM1
- **Data format:** GeoJSON

### Population Data

- **Source:** WorldPop
- **Geographic level:** Nigerian states
- **Population data version:** WorldPop v3.0
- **Data format:** Spreadsheet

## Methodology

1. Downloaded Nigeria's first-level administrative boundaries.
2. Imported the boundaries into QGIS.
3. Obtained state-level population estimates from WorldPop.
4. Standardized mismatched state names between the datasets.
5. Joined the population table to the state boundary layer.
6. Converted the population field into a numeric field.
7. Applied graduated symbology to visualize population differences.
8. Added state labels and boundary outlines.
9. Created a professional print layout.
10. Exported the final map as an image and PDF where applicable.

## Outputs

- Processed Nigeria state population layer.
- QGIS project file.
- Final population distribution map.
- Project documentation.

## Key GIS Skills Demonstrated

- Vector data management
- Attribute-table inspection
- Table joins
- Field calculation
- Data cleaning
- Graduated symbology
- Map labeling
- Cartographic layout design
- Map export
- Git version control

## Limitations

- The map represents estimated population values from the selected WorldPop dataset.
- Population estimates may differ from official census figures.
- The map shows state-level variation and does not represent population distribution within individual states.

## Author

**Yusuf Mamman**

## License

This project is intended for educational and portfolio purposes. Data sources retain their respective licenses and attribution requirements.
