# World_Weather_Analysis

# Resources
- Data Sources: cities.csv
- Software: Python 3.7.6, Jupyter Notebook 6.4.5
- Libraries: NumPy, CitiPy, Pandas, Matplotlib
- Interchange formats/interfaces: OpenWeatherMap API, Google Places API, JSON

## Background
Working for PlanMyTrip – a travel technology company focused on hotel and lodging – head analyst Jack is requesting assistance collecting data that can be presented on the search page to help customers find their ideal hotel anywhere the world. To assist Jack, NumPy was used to generate a list of 1,500 random numbers between -90 and 90, which were assigned to the latitude variable and another 1,500 for longitude. With these values combined into sets, city and country codes were assigned using the CitiPy module. OpenWeatherMap API was accessed to parse data in JSON format, which was then converted to a data frame with variables that included city, country, date, latitude and longitude, and current weather conditions, based on the randomly generated latitude and longitude coordinates.

After a brief interlude to demonstrate weather-related scatterplots and regression lines to curious STEM students, Google Maps API was employed to create heat maps specific to the different weather conditions. Through input statements, customer interest in destinations that ranged between 75- and 90-degrees Fahrenheit necessitated construction of a new data frame based on those parameters. Yowza! What a cold snap this year … it’s an unusual 45 degrees in Miami. These customers may have to consider more tropical destinations. Hotel information was imported with Google Places in JSON format and converted to a final data frame. A heat map specific to these locations was created. Markers were added to provide location, weather and hotel information.

## Deliverable 1: Retrieve Weather Data
With all this experience, a new set of data were created based on 2,000 randomly chosen values for both latitude and longitde. Work mirrored the earlier effort.  

![ALT Text](https://user-images.githubusercontent.com/30667001/151229583-61d12180-c88d-4a13-a479-1ffa0f7ff4ea.png)


## Deliverable 2: Create a Customer Travel Destinations Map
The same customer weather preferences were used to identify potential travel destinations and nearby hotels. Pop-up markers with information about location, weather description and hotel name highlighted the options.

![ALT Text](https://user-images.githubusercontent.com/30667001/151229972-d69219be-7e0c-49da-89d7-e0cf4390a70d.png)

## Deliverable 3: Create a Travel Itinerary Map
Narrowing the list to four cities of interest in Australia, a marked travel route was constructed from Hervey Bay to Charters Towers, with a stop in Alice Springs, and a visit to Cairns along the way, before heading back to Hervey Bay. A second map with pop-up information complimented the first and allows for additional travel planning.

![ALT Text](https://user-images.githubusercontent.com/30667001/151230421-6a7430f9-34e4-404e-8bf3-279ee4989ce1.png)
