# **Same-Day Delivery Eligibility using Geospatial Data (Massachusetts)**

This project analyzes and determines whether an entered address falls within the same-day delivery zones in Massachusetts, U.S., using geospatial data. It combines geographic data analysis, regression modeling, and visualization techniques to provide an efficient and scalable solution.

## **Table of Contents**
1. [Overview](#overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)

## **Overview**
This project determines whether a user-provided address is eligible for same-day delivery based on its distance from a warehouse and its inclusion within predefined delivery zones. The analysis leverages shapefiles for polygon-based boundaries and a radius-based distance model.

## **Features**
- Convert user-entered addresses into geographic coordinates using geocoding APIs.
- Analyze delivery zones with polygon-based (shapefile) and radius-based boundaries.
- Build a regression model to predict delivery eligibility.
- Visualize delivery zones and address eligibility using interactive maps.
- Perform scalable calculations for multiple addresses with optimized computational techniques.

## **Technologies Used**
- **Programming Language:** Python
- **Libraries:** 
  - [GeoPandas](https://geopandas.org/) - Geospatial data analysis
  - [NumPy](https://numpy.org/) - Efficient numerical computations
  - [Matplotlib](https://matplotlib.org/) - Data visualization