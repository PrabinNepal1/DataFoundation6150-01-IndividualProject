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

## References
1. **OpenAddresses - U.S. Northeast**  
   OpenAddresses - U.S. Northeast. Kaggle. Published on July 27, 2017. Accessed on December 8, 2024.  
   [Dataset URL](https://www.kaggle.com/datasets/openaddresses/openaddresses-us-northeast?select=ma.csv)

2. **MassGIS Data: 2020 U.S. Census Towns**  
   MassGIS. 2020. MassGIS Data: 2020 U.S. Census Towns. Mass.gov. Accessed December 8, 2024.  
   [Learn More](https://www.mass.gov/info-details/massgis-data-2020-us-census-towns)

3. **Python Programming Language**  
   Python Software Foundation. Accessed December 8, 2024.  
   [Official Website](https://www.python.org)

4. **scikit-learn: RandomForestClassifier**  
   scikit-learn. Accessed December 8, 2024.  
   [Documentation](https://scikit-learn.org/1.5/modules/generated/sklearn.ensemble.RandomForestClassifier.html)

5. **Distance on a Sphere: The Haversine Formula**  
   Esri Community. Published December 12, 2021. Accessed December 8, 2024.  
   [Read More](https://community.esri.com/t5/coordinate-reference-systems-blog/distance-on-a-sphere-the-haversine-formula/ba-p/902128#:~:text=For%20example%2C%20haversine(%CE%B8),longitude%20of%20the%20two%20points)
