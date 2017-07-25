# clustering-with-NBA-stats
Pulls stats from basketball-reference.com and does k-means clustering

All the code is in the notebook ``nba_data.ipynb``

The clusters are visualized in 2D using PCA (Principal Component Analysis)

It gets data from reading the HTML on a target page from basketball-reference.com. It is pretty robust to changing the target page. You need to inspect the HTML and find the id of the table for different pages. 

Here is an example of the figures produced using 3 clusters using the total stats from 2017 https://www.basketball-reference.com/leagues/NBA_2017_totals.html

![all clusters](https://github.com/alcolado/clustering-with-NBA-stats/blob/master/all_clusters.png)

![cluster 0](https://github.com/alcolado/clustering-with-NBA-stats/blob/master/cluster_0.png)

![cluster 1](https://github.com/alcolado/clustering-with-NBA-stats/blob/master/cluster_1.png)

![cluster 2](https://github.com/alcolado/clustering-with-NBA-stats/blob/master/cluster_2.png)
