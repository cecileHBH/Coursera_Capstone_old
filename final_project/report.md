# Final Report

## Finding a city "twin"

### Introduction

As an entrepreneur, you have successfully launched your business in a city. You have made a lot of research to assess this was the right place to launch and now it is time to scale and expand to another city. 
You could do the same research to find another city having the same requirements than the initial one but what if there was some other key specificities you missed ?
By looking for a "twin" for your original city, you automate your launching process and can discover more peculiarities that would make a city the perfect next place to launch.
Choosing the right city is key to a new successful launch and using data science could be a real benefit.

### Data

We will take Paris (France) as the original city, its venues data will be our point of comparison for the other cities.

First, we will define a shortlist of cities to analyze and compare to the first one. This list will specified based on basics criterias by the business so we don't analyze cities that do not match the right timezone or language for example. We will sefine this list with a few european cities : Lyon (France), Lisbonne (Portugal), Londres (Grande Bretagne), Berlin (Germany) and Milano (Italy)

Assuming a city characteristics stand in its offered amenities, we will use the Foursquare API to collect data of venues from specific cities.
For every city, we will search venues for every neighborhood per main category

Using different information like the categories (such as transportation, restaurants, outdoor and education) of the venues and the trending venues, we will identify patterns and compare cities.

## Source of data

* Paris neighboroods data : [opendata.paris.fr](https://opendata.paris.fr/explore/dataset/arrondissements/export/?location=12,48.85889,2.34692&basemap=jawg.streets&dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6ImFycm9uZGlzc2VtZW50cyIsIm9wdGlvbnMiOnt9fSwiY2hhcnRzIjpbeyJhbGlnbk1vbnRoIjp0cnVlLCJ0eXBlIjoiY29sdW1uIiwiZnVuYyI6IkFWRyIsInlBeGlzIjoibl9zcV9hciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiMwMDMzNjYifV0sInhBeGlzIjoibl9zcV9hciIsIm1heHBvaW50cyI6NTAsInNvcnQiOiIifV0sInRpbWVzY2FsZSI6IiIsImRpc3BsYXlMZWdlbmQiOnRydWUsImFsaWduTW9udGgiOnRydWV9)


### Methodology

#### Collecting city data
As we cannot get all the venues of a city easily, we collect a dataset consisting of the first 50 venues for every neighborhood per main category using Foursquare API. 

#### Cleaning data
We might have duplicates using this methodology because we collected the venues per neighborhood using their latitude, longitude and a radius, some venues might overlap over multiple neighborhood so we will remove every duplicates.

#### Finding similarities

### Results

### Discussion

### Conclusion
