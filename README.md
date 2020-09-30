# Homework-6 This is a weather dashboard using the OpenWeather API. Search by city name and an ajax call is made to the api with the day's current temperature, humidity, windspeed, an icon, and short-form desription, as well as the city name and date rendered from the returning resource. Current weather is updated every three hours, and the app uses a separate Date object to limit forecast data to the noon hour for the same city, for five days following. Searches are rendered as list items, and their data are saved to locol storage. The list is re-rendered on reload as long as the local storage has not been cleared. The logic is constructed around several arrays and a counter, to loop through the forecasted weather data and filter the noon-hour data, to set the local storage keys, and corresponding values in such a way as to maintain the order in which each search was added, as well as to give each list Item a unique id matching in value to the numberical key in local storage. Jquery selectors and methods build out the DOM. A refactor could certainly help this app. Im unhappy with the way the orange card presenting the description of the current weather is not in line with its headline, nor is it inline with the left margins of the text above it. An improvent to that feature might also include changing colors based on weather conditions. The logic, while fun for me while solving, might not be fun for someone else to read. Adding a feature which renders the last data viewed on reload was a requirement for this assignment. The pieces are in place for this, however adding it will have to wait for another time.          
