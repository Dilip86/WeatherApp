# Weather App

![image](https://github.com/Dilip86/WeatherApp/assets/97818951/651475a4-5174-4afa-b03e-87915f0b3417)



This is a simple web-based weather application that allows users to check the weather for a specific city. It uses the OpenWeatherMap API to fetch weather data and displays it on the webpage.

## Features

- Enter the name of a city in the search input.
- Click the search button to retrieve and display weather data for the entered city.
- Displays temperature, city name, humidity, and wind speed.
- Shows a weather icon based on the current weather conditions.

## Technologies Used

- HTML
- CSS (with Bootstrap Icons)
- JavaScript

## How to Use

1. Clone this repository to your local machine:


2. Open the `index.html` file in your web browser.

3. Enter the name of a metropolitan cities in the input field and click the search button.

4. The weather information for the entered city will be displayed.

## API Integration

This app uses the OpenWeatherMap API to fetch weather data. You will need to obtain an API key from [OpenWeatherMap](https://openweathermap.org/) and replace the `apiKey` variable in the `script` section of `index.html` with your own API key:

```javascript
const apiKey = "d77fef5917cb9405d952cf4ebb78a6e2";
