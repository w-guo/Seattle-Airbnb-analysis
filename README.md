# Seattle Airbnb Analysis

 This project focuses on exploring key insights of Seattle Airbnb market from the perspectives of interactive data visualization and text mining. Given the lastest Seattle Airbnb data, we are motivated to answer the following business questions from three aspects:

* Location impact on Seattle Airbnb market
    - Where are the listings located and what are the average prices of these listings by neighbourhood?
* Advice for tourists 
    - What is the availability of the accommodations and what is the price trend in the near future?
* Insights for hosts
    - What do tourists like about their accommodations and what do they usually complain about if they had a bad experience?

The analysis provided here gives a general overview of the Airbnb market in Seattle, and can also serve as a guide to the future visitors.

 ### File descriptions

This repository contains a Jupyter notebook `Seattle_Airbnb_analysis.ipynb` to showcase the work related to the above questions. 

* Please view it via nbviewer at [here](https://nbviewer.jupyter.org/github/w-guo/Seattle-Airbnb-analysis/blob/2fbf64cfd8f869df41f91d1bc9ee5f2e1fafc33d/Seattle_Airbnb_analysis.ipynb). The interactive graphs in the notebook are unable to display as any `.ipynb` file in a GitHub repository will be rendered as a static HTML file.
  
The dataset used here includes the following files that can be downloaded from [Inside Airbnb](http://insideairbnb.com/get-the-data.html):

* `listings.csv.gz`: detailed Listings data for Seattle
* `calendar.csv.gz`: detailed Calendar data for listings in Seattle
* `reviews.csv.gz`: detailed Review data for listings in Seattle
* `neighbourhoods.geojson`: GeoJSON file of neighbourhoods of the city

All the files are compiled on October 25, 2020.

### Prerequisites

To run `Seattle_Airbnb_analysis.ipynb`, the following Python libraries are required to be installed: `pandas`, `matplotlib`, `seaborn`, `folium`, `geopandas`, `branca`, `plotly`, `re`, `nltk`, `vaderSentiment`, `scikit-learn`, `wordcloud` and `langdetect`.

### Results

The results of the analysis are best presented in the accompanying [blog post](https://wguo.rbind.io/post/seattle-airbnb-analysis/).

### Acknowledgements

Credit to Inside Airbnb for hosting the data. The data behind the Inside Airbnb site is web scraped from publicly available information from the Airbnb site. The data has been analyzed, cleansed and aggregated to facilitate public discussion.

Blog references: 
* https://www.kaggle.com/erikbruin/airbnb-the-amsterdam-story-with-interactive-maps
* https://jingwen-z.github.io/airbnb-paris-analysis/