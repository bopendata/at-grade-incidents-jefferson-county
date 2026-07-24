# At-Grade Highway–Rail Crossing Safety and Network Dashboard

**Location:** Jefferson County, Alabama  
**Version:** 1.0

## Overview

This interactive dashboard was developed using **QGIS2Web** to visualize at-grade highway–rail crossing locations, incident history, fatalities, injuries, traffic volumes, and supporting transportation network datasets for Jefferson County, Alabama.

The dashboard is intended to support transportation safety analysis, infrastructure planning, and accessibility studies. The package includes the interactive dashboard along with processed datasets used for visualization and analysis.


## Project Attribution

This dashboard and associated datasets were developed as part of the **B-Open Project**, a research initiative at the School of Engineering, University of Alabama at Birmingham (UAB). The work was developed by the research teams of Dr. Avinash Unnikrishnan and Dr. Moiz Usmani.


## Contents

```
index.html              Main interactive dashboard
data/                   Spatial data files used by the dashboard
dataset/                Processed datasets and downloadable data products
css/                    Stylesheets
js/                     JavaScript files
legend/                 Map legend resources
webfonts/               Font resources used by the dashboard
documentation/          Detailed methodology, workflow, and dataset documentation
README.md               This file
```

## Opening the Dashboard

Open the file:

```
index.html
```

using a modern web browser such as:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox

If the dashboard does not display correctly due to browser security restrictions, serve the folder using a local web server (for example, VS Code Live Server).


## Dashboard Layers

The dashboard includes the following datasets and map layers:

- At-Grade Highway–Rail Crossings
- Highway–Rail Crossing Incident Summary
- Road Network
- Functional Road Classification
- North American Rail Network
- County Boundaries


## Data Sources

The dashboard was developed using publicly available datasets from the following sources:

- Federal Railroad Administration (FRA) – Highway-Rail Grade Crossing Incident Data (Form 57)
- Federal Railroad Administration (FRA) – Highway-Rail Crossing Inventory
- North American Rail Network (NTAD/BTS)
- City of Birmingham GIS Mapping Files
- Overpass Turbo (OpenStreetMap)
- TIGER/US Census Boundary Data

Complete source information, metadata, methodology, and supporting documentation are available in the accompanying `documentation/` folder.

## Processed Dataset

The processed analytical dataset includes information such as:

- Crossing ID
- Street Name
- Trains per Day
- Incident Counts
- Fatalities
- Injuries
- Annual Average Daily Traffic (AADT)
- Geographic Coordinates

The processed datasets are provided in:

- GeoJSON format for spatial visualization and analysis
- Microsoft Excel format for tabular analysis and reporting


## Data Processing

Incident records for Jefferson County were extracted from the FRA Highway–Rail Grade Crossing Incident dataset.

Records from 2015 onward were summarized by crossing and year, then combined with crossing inventory information and geographic coordinates to create the datasets used in this dashboard.


## Documentation

For a detailed description of:

- Data sources
- Data processing workflow
- Methodology
- Dataset structure
- Complete data dictionary

please refer to:

`documentation/` folder


## Notes

This dashboard is intended for visualization and analytical purposes. Users requiring the latest available information should refer to the original data providers.


## Citation

If you use this dataset, dashboard, or any derived products, please cite:

> Author(s). (Year). *Title of the manuscript*. SSRN / arXiv.  
> DOI/Identifier: `<DOI or arXiv ID>`  
> Available at: `<Preprint URL>`

Please use the journal citation instead if a peer-reviewed version becomes available.


## Contact

For questions regarding this dataset or dashboard, please contact:

**Name:**  
**Affiliation:**  
**Email:**  