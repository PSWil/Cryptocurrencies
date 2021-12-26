# Cryptocurrencies

## Overview

For this project I created a report for an investment bank that is offering investment portfolios that include cryptocurrencies. The report includes cryptocurrencies that are trading currently and how they might be grouped to better improve performance. I am using unsupervised machine learning on data provided by CryptoCompare.

## Results

After cleaning up the data to include actively trading cryptocurrencies wtih a defined algorithm and a complete set of data, there were 532 different cryptocurrrencies in the data set. From there I created a three dimisional graph to show how the different cryptocurrencies are grouped together. Each point includes its name as well as the algorithm used to create the currency.

### 3D Scatter Cluster

![3D_Scatter_Cluster](https://github.com/PSWil/Cryptocurrencies/blob/main/Images/3D_Scatter_Cluster.png)

I then created a two dimisional graph to show the relationship between total coin supply and total coins mined to show how each currency compares to the rest. Each point includes its currency name.

### HVPlot Scatter

![hvplot_scatter](https://github.com/PSWil/Cryptocurrencies/blob/main/Images/hvplot_scatter.png)

## Summary

(Finally we are left with four different groups. Two groups are clumped very closely together with most currencies falling into one of these two groups. One group has a few different currencies that are farther away from the others and then there is the last group that only have one currency. This shows that there are lot of currencies that perform similarly while there are a few that are outliers. These outliers could be over performers or under performers, but I would need to perform more analysis to figure that out. One thing that I can connect is by looking at the total coin supply vs total coins mined graph. The two main groups have most of there data points scattered between 0% and 40% of the largest currency based on volume. The group with a few currencies are are very close to 0% of the largest currency, while the group with just one currency is at 100% as it is the largest currency.)
