# <p align="center"> FIND THE BEST LOCATION FOR YOUR BUSINESS</p>


  <p align="center"> <img  src="https://miro.medium.com/fit/c/256/256/1*NFwzjjur2atssvIlGia0AQ.jpeg"></p>


<p align="center">Project for Ironhack's Data Analytics Bootcamp</p>


---

## Overview

The goal of this project is for me to practice what I have learned in the MongoDb Geoqueries chapter of the Ironhack program. For this project, I start with [The Crunchbase Dataset](https://data.crunchbase.com/docs) and [Google Places API](https://developers.google.com/places/web-service/intro). I import it and use my newly-acquired skills to build a data pipeline that processes the data and produces map with the best location for your business and the services that we want near of it. I try demonstrate my proficiency with the tools we covered (functions, list comprehensions, string operations,web scraping, mongoDB queries, pymongo, folium and APIs manage) in my pipeline.

---
## Goals

- Nobody in the company likes to have companies with more than 10 years in a radius of 2 km.
- Developers like to be near successful tech startups that have raised at least 1 Million dollars.
- Executives like Starbucks A LOT. Ensure there's a starbucks not to far.
- The CEO is Vegan, need a location with vegan restaurants near.
- All people in the company have between 25 and 40 years, give them some place to go to party (night clubs)
- 30% of the company have at least 1 child. Find schools close.

## Results

According to my results the best place to achieve the goals proposed is the __San Francisco (USA)__





## Project Structure

The project folder is structured in the following way:

* __cleaning.py__ : that contains the code to clean the raw database.

* __Geolocations.ipynb__ : file with the geoqueries, api connection and folium map.

* __Functions__ : Folder where the functions files are stored.

* __Ouput__ : Folder that contains the cleaned datasets in CSV and JSON format. It also contains the html map of my data pipeline query.

* __SRC__: Images and resources.

### 1 - Clean and Analysis

1. I acquire the data from the dataset, make some queries with Pymongo.
2. Create the functions to explore the dataset and clean it.
3. Generate a new dataset to work with it.
4. Import the new dataset with Mongo Compass

### 2 - Data Processing and Geoqueries

1. Filter the dataset to get best places.
2. Apply some functions to rank locations and choose a place.
3. Connect to Google Places API and get locations of the conditionals (Starbucks, Vegan Restaurants, Night Clubs, Schools and another tech companies)
4. Create a map with folium and show icons with every location.

## Links & Resources​
- https://developers-dot-devsite-v2-prod.appspot.com/maps/documentation/javascript/examples/geocoding-reverse
- https://docs.mongodb.com/manual/geospatial-queries/
- https://developers.google.com/maps/documentation/geocoding/intro
- https://developers.google.com/maps/documentation/geocoding/start
- https://data.crunchbase.com/docs
- https://developers.google.com/places/web-service/search
- https://www.youtube.com/watch?v=PtV-ZnwCjT0

