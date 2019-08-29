# APIs
Zomato's APIs give access to the freshest and most exhaustive information for over 1.5 million restaurants across 10,000 cities globally.
Due to Zomato API Basic Plan restriction, we cannot collect enough data for analysis. To overcome this problem ‘Zomato.csv’ file is provided to analyse the data deeply and to get useful inference.
Data has been collected from the Zomato API in the form of .json files(raw data) using the following url and stored in CSV file -
https://developers.zomato.com/api/v2.1/search?entity_id=1&entity_type=city&start=1&count=20 
Download Link


Details of zomato.csv -


Restaurant Id : Unique id of every restaurant across various cities of the world
Restaurant Name : Name of the restaurant
Country Code : Country in which restaurant is located
City : City in which restaurant is located
Address : Address of the restaurant
Locality : Location in the city
Locality Verbose : Detailed description of the locality
Longitude : Longitude coordinate of the restaurant's location
Latitude : Latitude coordinate of the restaurant's location
Cuisines : Cuisines offered by the restaurant
Average Cost for two : Cost for two people in different currencies
Currency : Currency of the country
Has Table booking : yes/no
Has Online delivery : yes/ no
Is delivering : yes/ no
Switch to order menu : yes/no
Price range : range of price of food
Aggregate Rating : Average rating out of 5
Rating color : depending upon the average rating color
Rating text : text on the basis of rating of rating
Votes : Number of ratings casted by people

