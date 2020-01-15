# Segmenting and Clustering Neighbourhoods in Toronto

## Introduction

In this notebook, I convert a collection of Toronto addresses (obtained via web parsing) into their equivalent latitude and longitude values using a geocoding API. Secondly, I use the Foursquare API to explore neighbourhoods in Toronto. Then I use the explore function to get the most common venue categories in each neighbourhood, and additionally use this feature to group the neighbourhoods into clusters. To compute these clusters, the k-means clustering algorithm will be used. Finally, I use the Folium library to visualize the neighbourhoods in Toronto and their emerging clusters.
