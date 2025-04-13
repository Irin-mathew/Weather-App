# Weather Forecast App

A simple, elegant web application that allows users to check the current weather and hourly forecast for any city around the world.


## Features

- Search for weather information by city name
- Display current temperature in Celsius
- Show weather description and corresponding icon
- View 24-hour forecast with temperature and conditions
- Responsive design with a modern glass-morphism UI style

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- OpenWeatherMap API

## Setup Instructions

1. Clone the repository to your local machine
2. Open the project folder in your code editor
3. Replace the API key in `script.js` with your own OpenWeatherMap API key
   ```javascript
   const apiKey = "YOUR_API_KEY_HERE";
   ```
   You can get a free API key by signing up at [OpenWeatherMap](https://openweathermap.org/api)
4. Open `index.html` in your web browser

## How It Works

1. Enter a city name in the input field
2. Click the "Search" button
3. The app fetches data from the OpenWeatherMap API
4. Current weather information is displayed, including:
   - City name
   - Current temperature
   - Weather description
   - Weather icon
5. Below the current weather, you'll see an hourly forecast for the next 24 hours

## Code Structure

- `index.html` - The main HTML structure
- `style.css` - Contains all styling for the application
- `script.js` - Handles API calls and DOM manipulation

## API Information

This app uses two endpoints from the OpenWeatherMap API:
- Current weather: `###########################`
- Forecast data: `############################`

## Known Issues

- Temperature is only displayed in Celsius
- Limited error handling for network issues
- No geolocation feature to detect user's location

## Future Improvements

- Add temperature unit toggle (Celsius/Fahrenheit)
- Implement geolocation to automatically detect user's city
- Add dark/light theme toggle
- Include more weather details (humidity, wind speed, etc.)
- Add a 5-day forecast view

## License

[MIT License](LICENSE)

## Acknowledgements

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
- Weather icons from OpenWeatherMap's icon set
