# AirBnB-VIE-Analysis

sklearn, geopandas, statsmodels, OLS Regression, k-means & Davies-Bouldin clustering

Data Analytics project to gain insights of the AirBnB market in Vienna. With that, I want to see why AirBnB's offers cost their price, what areas are pricier or cheaper and whether I can predict a price for a new offer.  

## Data
The data was downloaded in August 2020 from [insideairbnb](http://insideairbnb.com/get-the-data/). The dataset is cleaned and prepared for analysis in the first half of the notebook. The shape file of Vienna's districts was downloaded from [data.gv.at](https://www.data.gv.at/katalog/dataset/stadt-wien_bezirksgrenzenwien#resources). 


## Result

### Amneties

The best predictors for a high price offer are TV and air conditioning, while bed linens decrease the perceived price, according to the OLS regression. Most interestingly, a coffee machine does not increase the offer's price, although not being statistically significant. This makes me doubt my analysis :).

### Heat Map of Vienna

This heat map visualises the OLS parameters that describe the price of AirBnB offerings, with an intercept of 124.18 EUR. *Red* districts have higher prices, and *blue* districts have lower prices. With this heat map, you can quickly estimate in what districts you could start your AirBnB business or book cheaper offers. 

![image](https://github.com/RobbsX/AirBnB-VIE-Analysis/assets/79597633/d575e27a-c788-47c0-a389-7a2eb6c54b13)


## Further Steps

It would be most interesting to make a full-through analysis for starting an AirBnB business, to make a tool for deciding whether a unit is a potential profit machine. 
