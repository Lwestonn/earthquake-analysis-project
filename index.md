
# Earthquake Analysis Project

## Overview
This project explores earthquake data, visualizing patterns in frequency, magnitude, and depth. It includes:
- **Two static maps** showcasing earthquake trends.
- **One interactive map** for exploring individual earthquake events.

---

## Dataset Description
- **Source**: [USGS Earthquake Catalog](https://earthquake.usgs.gov/earthquakes/search/)
- **Prepared By**: United States Geological Survey (USGS)
- **Last Updated**: Includes data up to November 2022.
- **Transformations**:
  - Filled missing values in `alert`, `continent`, and `country`.
  - Extracted date components (year, month, day).
  - Aggregated data by region for static maps.

---

## Outputs

### Static Maps
1. **Earthquake Frequency by Region**  
![Earthquake Frequency by Region](/content/earthquake_frequency_map_enhanced.png)

2. **Average Magnitude and Depth by Region**  
![Average Magnitude and Depth by Region](/content/average_magnitude_depth_map.png)

---

### Interactive Map
Explore earthquake events interactively:  
[Interactive Earthquake Map](/content/earthquake_interactive_map.html)

---

## Author
- **Name**: [Lucas Weston]
- **Course**: Command-Line GIS, Fall 2024
