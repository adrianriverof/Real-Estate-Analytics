# Real State Market Analysis for Tourist Rentals

This analysis project is part of a course in data science. The exercise simulates that we belong to a real estate company, and we carry out an analysis of tourist apartments in Madrid with the objective of renting them out as tourist apartments.

Disclaimer: this project was initially done in Spanish, and later translated the important prose. It's a bit sloppy, next time I'll do it in English from the beggining.


### Overview of the project


We gathered the main data on tourism apartments from airbnb (not included in this repo, you can get it [here](https://insideairbnb.com/get-the-data/)), wich came in different csv files. We condensed the useful data into a dataframe, then cleaned and analized it complementing with more data for the pricing. 
After that, I made it again but for the Valencia city.

##### Conclusions of the analysis

- we identified 10 neighborhoods that can maximize the cost-income ratio, and segmented them by type and quality.
- we found that the optimal option is to look for properties with one room that can accommodate 3 guests.
- for the scope of this analysis, it seems that proximity to points of interest is not very relevant.
- There's a market opportunity on renting properties in specific neiborhoods for moments of high sporting interest.

[Results notebook](https://github.com/adrianriverof/Real-State-Market-Analysis-for-Tourist-Rentals/blob/main/Madrid/6-%20Results.ipynb)

<img src="https://github.com/user-attachments/assets/0c9801df-364e-4ffb-bce7-909a766ff745" alt="Districts of Madrid price vs rent" width="600" height="400">


##### Challenges faced

Some data had to be scraped from a webpage, using a chrome extension. The Valencia case data was more tricky to work around, because there was less uniformity in the district organization, and I had to manually introduce some of the data. There was some missing data that could be imputed in the data cleansing phase.

##### Interesting techniques

- I created a database using SQLite and acceded with sqalchemy
- I used folium to easily provide map visualizations
- I created a subcube to easily access some key data during the analysis

<img src="https://github.com/user-attachments/assets/235a738c-5872-4890-8885-ee23869c8471" alt="Prices in a district of Valencia" width="400" height="250">




