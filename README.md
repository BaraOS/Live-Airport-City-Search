# Live-Airport-City-Search

This application lets you perform a live search for Airports and Cities through the Amadeus [Airport & City Search API](https://developers.amadeus.com/self-service/category/air/api-doc/airport-and-city-search).
The implementation is done through jQuery Autocomplete with Node and Express as the backend for which connects ot the Amadeus API


# Running the code

1. In order to use the applicaiton you must obtain a valid API Key from [Amadeus](https://developers.amadeus.com/get-started/get-started-with-self-service-apis-335) 
and paste it within App.js

```
clientId= 'id'
clientSecret= 'secret'
```
2. Start the server

```
node app.js
```

# Built Using
* Express.JS
* Node.JS
* jQuery 

![Alt text](https://github.com/BaraOS/Live-Airport-City-Search/blob/master/readme_media/live_search.gif?raw=true)
