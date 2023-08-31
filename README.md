# City Development Analysis

This repository contains code for analysing major new commercial and residential property development data in the City of Melbourne municipality. The dataset, called the "City of Melbourne Development Activity Monitor," provides insights into development activities such as completed, under construction, planned, or potential projects across 13 small areas within the city.

## Dataset Information

The dataset contains information about developments that meet specific criteria to be included in the Development Activity Monitor. These criteria include:

- 10 or more residential dwellings
- 10 or more student apartments
- 10 or more student beds
- 10 or more institutional accommodation beds (from December 2010)
- 10 or more serviced apartments
- 10 or more hotel rooms
- 10 or more hostel rooms
- 10 or more child care centre places (from December 2010)
- At least 500m² of net lettable office floor space
- At least 500m² of net lettable retail floor space
- At least 500m² of net lettable industrial floor space (from December 2010)
- At least 500m² of net lettable storage floor space (from December 2010)
- At least 500m² of net lettable educational floor space (from December 2010)
- At least 500m² of net lettable hospital/clinic - floor space (from December 2010)
- At least 500m² of net lettable indoor entertainment/recreational floor space (from December 2010)
- At least 500m² of net lettable public display floor space (from December 2010)
- At least 500m² of net lettable community use floor space (from August 2011)
- The dataset is valuable for informing short to medium-term supply forecasts in both commercial and residential markets.

Dataset Published Date: 07/03/2023

Dataset Source: [City of Melbourne Development Activity Monitor](https://data.melbourne.vic.gov.au/explore/dataset/development-activity-monitor/information/)

## Dependencies

The following Python libraries are used in this analysis:

- pandas
- numpy
- matplotlib
- sklearn
- pyclustering

# Code Files

City-of-Melbourne-Development-Activity-Monitor_Analysis.ipynb

This Jupyter Notebook contains the entire analysis workflow. It includes data loading, pre-processing, visualisation, clustering using K-means and hierarchical clustering, and evaluation of clustering results.

# Analysis Overview

The analysis aims to provide insights into the development activities in different suburbs, relationships between variables, and clustering of development activities. Clustering results are evaluated using silhouette coefficients and purity scores. The results highlight the optimal number of clusters and the clustering algorithm with the best performance for this dataset.

The analysis helps us understand the development landscape in the City of Melbourne municipality. It showcases the distribution of developments across suburbs, the effectiveness of clustering algorithms, and the factors influencing development activities.

Feel free to modify the code, explore different analyses, or adapt it to other datasets to gain further insights into city development activities.