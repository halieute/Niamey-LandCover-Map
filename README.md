# LandCover Map of Niamey

This project is focused on generating a land cover map for Niamey using Sentinel-2 imagery and the Dynamic World Land Cover dataset via Google Earth Engine.

## Overview
This script performs the following tasks:
- Initializes the Earth Engine library.
- Loads the shapefile asset for the region of interest (Niamey).
- Creates a Sentinel-2 image composite for the specified date range.
- Generates a land cover map using the Dynamic World dataset and clips it to the region of interest.
- Adds a customized legend to the map.
- Exports the clipped land cover map to Google Drive.

## Requirements
- Python 3.x
- Google Earth Engine API
- Geemap library

