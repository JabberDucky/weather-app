# Weather Forecasts by Jabberducky

The Weather App is a simple web application that allows users to check the current weather conditions for a specific location. It provides real-time weather data, including temperature, humidity, wind speed, and a brief description of the weather.

## Features
-**Real-time Weather Data**: The app fetches and displays up-to-date weather information for the selected location.
-**Location Search**: Users can search for the weather in a specific city or location by entering the name of the place.
-**Responsive Design**: The app is designed to be responsive and works well on both desktop and mobile devices.

## Technologies Used
-HTML
-CSS
-JavaScript

## Usage
1. Clone this repository to your local machine:
``` git@github.com:JabberDucky/weather-app.git ```
2. Open the project in Visual Studio Code or your preferred code editor.
3. Create a `config.js` file to add your API key (follow the example below). You can obtain a free API key from a weather data provider like [OpenWeatherMap](https://openweathermap.org/).
``` const API_KEY = 'YOUR_API_KEY'; ```
4. Open the index.html file in your browser or use a local development server.
5. Enter the location you want to check the weather for and either click the image of a magnifying glass or press the enter key.
6. The app will display the current weather conditions for the specified location.

## Configuration
In the `config.js` file, you need to replace `'YOUR_API_KEY'` with your actual API key from a weather data provider.
``` const API_KEY = 'YOUR_API_KEY'; ```

## API Integration
This app uses an external weather API to fetch weather data. You can replace the API with another provider if you prefer. Make sure to update the API endpoints and data parsing accordingly.

## Acknowledgments
Weather data is provided by [OpenWeatherMap](https://openweathermap.org/).
Icons by [IconFinder](https://www.iconfinder.com/).

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
[Jabberducky](https://github.com/JabberDucky)