# Stats 133 Final Project

Initialized on: Friday, October 30, 2015
This is the repository for the stats 133 final project.
Repository URL: https://github.com/a-ku/stats133_final

Team members:
* Alexander Ku
* Chris Matthews
* Shir Nehama

# This Repository

This repository's can be built by running the skeleton.R file ```rscript skeleton.R```. You can use ```git clone``` to clone this repository to your local machine.
Files:
* ```report``` contains an Rmd and pdf of the final report
* ```itinerary``` contains an Rmd and pdf of the generated itinerary
* ```code``` contains the code used to clean and process the data
* ```rawdata``` contains copies of the unprocessed data
* ```data``` contains copies of the cleaned processed data
* ```images``` contains image files used in the final report and itinerary
* ```skeleton.R``` generates the directories in this repository
* ```stat133_final.Rproj``` is an Rstudio project file



# Project Proposal

Topic: Trip Itinerary Builder

With the vast amount of experiences and opinions shared through online mediums such as Yelp, our group has decided to utilize this information to analyze business’ ratings with the objective to find the “best” recommended places in cities. Our project will answer the following scenario: Suppose you are traveling from San Francisco to a specific destination (city and state) in a certain month and you would like to know what is the best hotel to stay in that city. Moreover, once you find the best hotel, you only want to have to travel within a certain radius of the hotel to explore the city. To help in the vacation planning, we will utilize ratings of businesses from yelp data to output a recommendation for the best hotel in the trip destination along with 6 recommendations for top restaurants and entertainment within a limited distance of the hotel. To further “plan” the trip, we would analyze the expected flight cost of the trip as well as the weather to expect at the destination. In conclusion, this project will help us explore top activities and businesses in certain cities around the nation and even allow us to compare the type of activities that are most highly rated in different locations. Moreover, we will have a final function that recommends top activities and businesses for a potential vacation trip for a traveler from San Francisco. 

# Data Sources

We use three datasets for this project:
* Yelp academic business data ```yelp_academic_dataset_business.json```
* City weather data ```city_weather_raw.txt```
* City price parity data ```raw_price_parity_data.csv```

# Input/Output

The input to the program would be the city you want to travel to, the month (by default the current month), and a radius you are willing to walk within a city.
The output will be a PDF/HTML providing a trip itinerary with the following items:
* The best rated hotel in the city
* Select points of interest within a provided radius of the hotel
* The weather of the city annually, as well as during the month provided
* And a map of the city with the hotel and points of interests

