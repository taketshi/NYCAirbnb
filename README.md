# NYCAirbnb
## Motivation
This project was done in order to understand the distribution and prices of Airbnb in the city of New York.

## Description
It is performed a data analysis of datasets regarding prices, description and host of Airbnb's. Data is given in a rough format so cleaning was needed, and is also performed Feature Engineering. The data is from DataCamp.

## Build Status
The project is completed.

## Files
Data: 
- _airbnb_last_review.tsv_
- _airbnb_price.csv_
- _airbnb_room_type.xlsx_

Geocoordinates:
- _geocoordinates.json_: It was calculated the geocoordinates from place name. To avoid recalculation, it was saved here.

Notebook:
- _analysis.ipynb_: This notebook contains all the data cleaning, analysis and prediction.

## Packages
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- gender_guesser
- geopy: not required to run the notebook, was use to retrieve geocoordinates
