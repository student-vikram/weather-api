Title: Simple Weather App with City Search and Dynamic UI

Description: This HTML, CSS, and JavaScript code provides a basic weather app that allows users to search for a city and display current weather conditions, including temperature, humidity, wind speed, and weather icon.

Features:

City search bar with error handling for invalid input.
Dynamic weather information display based on API response.
Weather icons for different conditions like clouds, clear skies, rain, drizzle, and haze.
Clean and responsive layout with separate sections for search, error message, and weather data.
How It Works:

User enters a city name in the search bar.
Clicking the search button triggers the checkWeather function.
The function fetches weather data from the OpenWeatherMap API using the city name and API key.
If the city is valid, the API response is parsed and used to update the UI.
City name, temperature, humidity, wind speed, and weather icon are dynamically displayed.
In case of an invalid city, an error message is displayed and the weather section is hidden.
Dependencies:

OpenWeatherMap API key (replace cb003a5bcf78eb5f4c2abbf9d87bf5b0 in the code)
Images for weather icons (rain.png, clouds.png, clear.png, drizzle.png, mist.png)
style.css file for styling the UI elements
Getting Started:

Replace the API key in the code with your own.
Download the weather icons and place them in the same folder as the HTML file.
Run the HTML file in your browser and start searching for cities!
Customization:

You can modify the style.css file to customize the look and feel of the app.
Add more weather icons for other conditions.
Enhance the error handling for different API responses.
Integrate additional weather data like forecast or precipitation.
Note: This is a basic example and can be further extended with more functionalities and data visualization.

Feel free to contribute and improve this app!
