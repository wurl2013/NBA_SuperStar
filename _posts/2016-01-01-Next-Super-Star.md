---
layout: post
title: “Next Super Star”
categories: journal
tags: [documentation,sample]
image:
  feature: nbafans.png
  teaser: nbafans-teaser.png
  credit: Death to Stock Photo
  creditlink: ""
---

# **The Next Super Star in NBA?!**

## _Motivation_

Given the large basis of NBA audiences and increasing pursue for super stars, using past year data to analyze who is the next super star seems to be an interesting and meaningful question.


## _Questions_

Are there any statistical patterns in the players performance? Can we use the pattern to predict the potential stars?
What features do the potential stars and super stars share?

## _Methodology_

Using NBA statistic data, we would like to do some exploratory analysis and data visualization over “all stars” and “potential players” based on their first four seasons data
1 Data Scrapping2 K-means Cluster3 PCA and Data Visualization4 Compare player A and player B


## K-means Cluster

Cluster 4 is the largest proportion and cluster 1 is the smallest. The players in cluster 2 are mostly rookie players and all the players in cluster 3 are stars. In cluster 1,4, and 3, there are a few players are rookie players. Such that rookie stars in cluster 1, 4, and 3 may be potential candidates for next stars.

![Right-aligned image](https://mengxinji.github.io/NBA_SuperStar/images/pieCL.png)

![Light-aligned image](https://mengxinji.github.io/NBA_SuperStar/images/stackCl.png)

## PCA Visualization


<img src="https://mengxinji.github.io/NBA_SuperStar/images/cluster_plot_r.png" align="left" height="48" width="48" >

![alt tag](https://mengxinji.github.io/NBA_SuperStar/images/cluster_plot_r.png)


## Data Analysis

Based on the results of clustering, we would like to analyze why player A and player B are in the same cluster.James Harden vs. Micheal Cart-Williams Paul Millsap vs. Nerlen NoelTony Parker vs. Victor Oladipo

For James Harden vs. Micheal Cart-Williams, We compared their 3 point rate during last four regular seasons.

![alt tag](https://mengxinji.github.io/NBA_SuperStar/images/James_Michael.png)

For Paul Millsap vs. Nerlen Noel, we compared their BLK during last four regular seasons.

![alt tag](https://mengxinji.github.io/NBA_SuperStar/images/Millsap_Noel.png)

For Tony Parker vs. Victor Oladipo, we compared their Field Goal% during last four regular seasons.

![alt tag](https://mengxinji.github.io/NBA_SuperStar/images/Parker_Oladipo.png)


## Conclusion

Ideally, we would exploit an automatic clustering method that can correctly split all players into several clusters, and based on the similar pattern between all stars and potential stars to identify a forthcoming super star!
Micheal Cart-Williams 

Nerlen NoelVictor Oladipo




