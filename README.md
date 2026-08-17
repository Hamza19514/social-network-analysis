# Chicago Social Network Analysis

This project analyzes socioeconomic and demographic similarities among selected Chicago communities using network analysis and machine learning techniques.

## Project Overview

The analysis compares nine Chicago communities using demographic and socioeconomic features from 2018–2023, including:

* Median income
* Poverty
* Unemployment
* Education
* Broadband access
* Home ownership and renting
* SNAP participation
* Race and ethnicity demographics

The data was aggregated and normalized before calculating similarities between communities.

## Methods

The project uses several analytical techniques:

* Cosine similarity
* Euclidean distance
* Correlation analysis
* Network graph analysis with NetworkX
* Degree, closeness, and eigenvector centrality
* Louvain community detection
* K-Means clustering
* PCA visualization
* Assortativity analysis
* Clustering coefficients

## Key Findings

The analysis identified several groups of Chicago communities with similar socioeconomic characteristics.

* Lakeview, Lincoln Park, and Near North Side formed a highly similar cluster.
* Englewood and West Englewood showed very strong socioeconomic similarity.
* Irving Park, Portage Park, Jefferson Park, and South Lawndale formed another broader community group.
* Network and clustering methods revealed clear differences between higher-income, middle-income, and lower-income communities.

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* NetworkX
* Matplotlib
* Seaborn
* GeoPandas
* Jupyter Notebook

## Main Notebook

The complete analysis can be found here:

`chicago_social_network_analysis.ipynb`

## Author

Hamza Bu Obaid
