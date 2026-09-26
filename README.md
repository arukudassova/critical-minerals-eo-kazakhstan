# Remote Sensing and Geospatial Analysis of Critical Mineral Development in Kazakhstan

Undergraduate Capstone Project — Computational Sciences, Minerva University

## Overview

This repository holds the computational work for an undergraduate capstone. The capstone looks at how remote sensing and geospatial data can be combined to analyze and monitor critical-mineral development in Kazakhstan.

The project is in the **research and methodology-development stage**. The final research question and analytical framework are still being refined. This repository will change as data availability and the research gap become clearer.

## Current Research Direction

The broad aim is to see how multi-temporal Earth observation data, combined with geological, mining-site, and environmental datasets, can describe the extent and effects of critical-mineral development in Kazakhstan.

Analytical directions currently under evaluation (none of them are final):

- Change detection over time
- Land-surface and environmental change around mining sites
- Cross-site comparison
- Integration of multiple geospatial datasets
- Classification
- Satellite-based verification and monitoring

## Potential Data Sources

- **Earth observation:** Landsat and Sentinel imagery, mainly accessed through Google Earth Engine
- **Geological and mineral datasets:** mineral occurrence and deposit data
- **Mining and site-location datasets:** locations and attributes of mining and processing sites
- **Environmental and geospatial datasets:** land cover, hydrology, administrative boundaries, and similar reference layers

Specific datasets will be recorded in [`data/README.md`](data/README.md) once they are chosen.

## Tools

- Python
- Google Earth Engine (via `earthengine-api` and `geemap`)
- QGIS / GIS software
- Jupyter notebooks

## Repository Structure

```
critical-minerals-eo-kazakhstan/
├── README.md          Project overview (this file)
├── requirements.txt   Python dependencies
├── notebooks/         Exploratory analysis and Earth Engine experiments
├── src/               Reusable Python code, added as the analysis stabilizes
├── data/              Dataset documentation and small non-sensitive files
└── outputs/           Selected maps, figures, and tables
```

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
earthengine authenticate
```

Earth Engine authentication stores credentials outside this repository. Never commit credentials or API keys.

## Project Status

**Early stage: research and methodology development.**

No analysis has been completed yet. The research question, study sites, datasets, and methods are still being defined. The repository structure and contents will be updated as the project progresses.
