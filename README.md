# Extreme Precipitation Analysis in Ghana (2000-2010)

## Project Overview
This Python script analyzes and visualizes extreme precipitation events in Ghana over the period 2000-2010 using geospatial data processing and visualization techniques.

## Prerequisites
- Python 3.7+
- Required Libraries:
  - xarray
  - numpy
  - matplotlib
  - cartopy

## Installation
```bash
pip install xarray numpy matplotlib cartopy
```

## Data Requirements
- NetCDF file (`Africa_cru_data.nc`) containing:
  - Precipitation data
  - Temporal coverage: 2000-2010
  - Spatial coverage: Africa (Ghana region)

## Script Functionality

### Data Processing
1. Load precipitation dataset from NetCDF file
2. Select data for Ghana region
3. Filter precipitation events exceeding 250mm
4. Count extreme precipitation events per year

### Visualization
- Creates a 10-panel figure (2x5 grid)
- Each panel represents annual precipitation events
- Uses PlateCarree projection
- Includes geographic features:
  - Country borders
  - Coastlines
  - Rivers
  - Lakes
  - State boundaries

### Key Outputs
- Heatmap visualization of extreme precipitation events
- Annual count of precipitation events > 250mm
- Colorbar indicating event frequency

## Usage
```python
python ghana_precipitation_analysis.py
```

## Customization
- Adjust geographic bounds
- Modify precipitation threshold
- Change color scheme

## Diagnostic Information
The script provides:
- Yearly event count
- Precipitation range
- Total extreme events

## Potential Applications
- Climate change studies
- Hydrology research
- Disaster risk assessment

## Limitations
- Depends on source data quality
- Fixed 250mm threshold
- Restricted to 2000-2010 period


## Author
MENSAH BETHEL KOFI
```
