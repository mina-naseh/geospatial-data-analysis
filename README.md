# Bird Species Richness and Environmental Factors Analysis in Kenya

## Overview

This project focuses on analyzing bird species distribution and abundance in Kenya by integrating geospatial and statistical techniques. The objective was to explore how environmental factors such as elevation and precipitation influence bird abundance and to map species richness across the country, identifying biodiversity hotspots.

---

## Key Components

### 1. **Data Preprocessing**
   - Filtered and cleaned bird occurrence data specific to Kenya.
   - Extracted environmental variables (elevation and monthly precipitation) from raster datasets for each observation point.
   - Applied log-transformation and normalization to abundance data to address skewness and ensure comparability.

### 2. **Bird Abundance Analysis**
   - **Statistical Analysis**:
     - Explored relationships between bird abundance and environmental factors using correlation (Pearson, Spearman, Kendall) and ANOVA.
   - **Spatial Visualization**:
     - Created maps to illustrate bird abundance, log-transformed abundance, elevation, and precipitation patterns across Kenya.

### 3. **Species Richness Mapping**
   - **Point-Based Approach**:
     - Mapped bird species richness based on unique species observed at each location.
   - **Grid-Based Approach**:
     - Divided the study area into a grid and calculated species richness per cell, providing a more aggregated view of biodiversity distribution.

### 4. **Insights from Statistical Tests**
   - Conducted ANOVA to determine how bird abundance varies across elevation and precipitation bins.
   - Found weak correlations between environmental factors and bird abundance, highlighting the complexity of ecological relationships.

---

## Data Citation

This project utilized bird occurrence data from the Global Biodiversity Information Facility (GBIF). Please cite the data as follows:

**GBIF.org (26 October 2024) GBIF Occurrence Download https://doi.org/10.15468/dl.gu5t27**
