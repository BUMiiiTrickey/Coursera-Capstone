# Coursera_Capstone

## Business Problem
Leo is an owner of the Hotpot restaurant chain in China. Recently, his daughter came to Toronto to pursue her master's degree, so Leo decides to expand his business to Canada and move to Toronto with her daughter to take good care of her. Since Leo is not very good at English, he'd like to live in a neighbourhood where many Chinese people gather. However, since he also needs to make a living, he didn't want to open his hotpot restaurant in the places where too many Chinese restaurants existed, because too many competitors will make the business to be hard-hitting.So we need to help him find the place where is good to live and the other place for his business where is not very far away from home but without too many Chinese restaurants.

## Data Description
To solving Leo's problem, we will use the Foursquare location data and postal-code list data from Wikipedia and Geospatial_Coordinates data in combination. 
We firstly scraped the postal-code list from URL: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M. 
The list from Wikipedia includes Canadian Postal code with the beginning of M, and the corresponding Borough and Neighborhood. Then we combine the list table with Geospatial_Coordinates data which contains longitude and latitude. After these processes, we begin to explore the neighbourhoods in Toronto by using Foursquare location data to check out the appropriate neighbourhood for Leo to live and develop business.
