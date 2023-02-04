# Countries In Need
## Clustering Countries by Socio-economic and Health Factors

What we hope to answer in this notebook is finding the countries in need of the most aid based on socioeconomic and health factors. To do this we will be using K-means clustering and Hierachical clusting (unsupervised machine learning) to group the countries based on an array of variables. For the best result we will first do PCA (Principle Component Analysis) to reduce dimensionality as this will help with noise reduction from less important variables. Then we will train the models and visualize the groupings.

Features used in this clustering project:
- country
- child_mort
- exports
- health
- imports	
- income
- inflation
- life_expec
- total_fer
- gdpp

## Organization;

### Project is broken up into two main notebooks:

#### 1. Exploration
https://github.com/daikiminaki/Random_Data_Projects/blob/master/clustering_for_nonprofit_countries_in_need/country_data_exploration.ipynb

#### 2. Clustering
https://github.com/daikiminaki/Random_Data_Projects/blob/master/clustering_for_nonprofit_countries_in_need/country_data_clustering.ipynb


## Resources:

Data Used: 
https://github.com/daikiminaki/Random_Data_Projects/tree/master/clustering_for_nonprofit_countries_in_need/data

Final Ranking:
https://github.com/daikiminaki/Random_Data_Projects/blob/master/clustering_for_nonprofit_countries_in_need/country_ranking.csv
