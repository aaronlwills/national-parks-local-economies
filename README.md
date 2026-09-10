# National Parks and Local Economies

This project examines whether rural counties near U.S. national parks are more economically dependent on tourism than urban gateway counties.

Using county-level economic and geographic data, I identify counties within 30 miles of national parks and compare tourism-related employment across rural and urban areas. I then use spatial statistics and regression methods to examine geographic clustering and differences in tourism dependence.

## Methods

- Geospatial data processing with GeoPandas
- Choropleth mapping
- Global Moran's I
- Local Indicators of Spatial Association (LISA)
- OLS and spatial regression

## Main Findings

Rural gateway counties showed somewhat higher average tourism dependence than urban gateway counties, and rural counties were disproportionately represented in high-tourism clusters. However, the spatial regression results did not provide strong evidence that rural status alone predicts tourism dependence.

## Files

- `National_Park_Project.ipynb` — full data cleaning, spatial analysis, mapping, and regression workflow
- `final_report.pdf` — full written report with methodology, results, discussion, and limitations

## Data Sources

This project uses data from the National Park Service, U.S. Census Bureau, Bureau of Economic Analysis, and USDA Rural-Urban Continuum Codes.

## Project Context

Originally completed as a final project for GGIS 371 at the University of Illinois Urbana-Champaign in May 2026.
