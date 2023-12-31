# Weather App

This is a weather application built with React that displays the weather information for a given city. It fetches weather data from the OpenWeatherMap API and updates the background image based on the temperature.



- Allows the user to enter a city name in the input field to fetch the weather data for that city.
- Displays the current temperature, weather description, and city name along with an appropriate weather icon.
- Provides the option to toggle between Celsius and Fahrenheit temperature units.
- Changes the background image based on the temperature: a cool image for temperatures below 20°C (metric units) or 60°F (imperial units), and a hot image for higher temperatures.
- Shows additional weather information such as humidity, wind speed, and visibility.

## OpenWeatherMap API

This weather application utilizes the OpenWeatherMap API to fetch weather data. The API provides current weather data for any location worldwide, including temperature, weather conditions, wind speed, and more.

To fetch the weather data, the application uses the `getFormattedWeatherData` function from the `weatherService` module. This function makes a request to the OpenWeatherMap API with the specified city name and temperature units (metric or imperial) and retrieves the weather information as a response. The response data is then formatted and displayed in the application.

To use the OpenWeatherMap API in your own project, you will need to sign up for an API key at [https://openweathermap.org](https://openweathermap.org). Once you have the API key, you can replace it in the `weatherService.js` file with your own key.

