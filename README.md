# Real State Market Analysis for Tourist Rentals

### Overview of the project

The purpose of this project is to analize the market data on tourism rentals to see what insights can we obtain from it.

### Process

The main data on tourism apartments from Madrid and Valencia was gathered from airbnb (you can get it [here](https://insideairbnb.com/get-the-data/)), wich came in different csv files.
The useful data was processed into dataframes, then cleaned and complemented with more external data for the pricing. 
The analysis consisted in estimating the earn potential of each apartment, based on the estimated cost of the apartment, the quantity of guests and occupance ratios.

##### Conclusions of the analysis

- there are 10 neighborhoods that can maximize the cost-income ratio, segmented by type and quality.
- the optimal option is to look for properties with one room that can accommodate 3 guests.
- for the scope of this analysis, it seems that proximity to points of interest is not very relevant.
- There's a market opportunity on renting properties in specific neiborhoods for moments of high sporting interest.

[Results notebook](https://github.com/adrianriverof/Real-State-Market-Analysis-for-Tourist-Rentals/blob/main/Madrid/6-%20Results.ipynb)

<img src="https://github.com/user-attachments/assets/0c9801df-364e-4ffb-bce7-909a766ff745" alt="Districts of Madrid price vs rent" width="600" height="400">


##### Challenges faced

Some data had to be scraped from a webpage, using a chrome extension. The Valencia case data was more tricky to work around, because there was less uniformity in the district organization, and some data had to be manually introduced. There was some missing data that could be imputed in the data cleansing phase.

##### Techniques and Technology

- libraries: numpy, pandas, matplotlib, seaborn
- a database was created using SQLite and acceded with sqalchemy
- folium was used to easily provide map visualizations
- a subcube was created to easily access some key data during the analysis

<img src="https://github.com/user-attachments/assets/235a738c-5872-4890-8885-ee23869c8471" alt="Prices in a district of Valencia" width="400" height="250">




