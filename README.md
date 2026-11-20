# Weather Finder

A simple web app that shows the current weather for any city in the world. Type a location, click **Get Weather**, and see live conditions instantly.

## Features

- Search weather by city name
- Shows temperature (°C), weather description, humidity, wind speed (km/h), and location with country
- Displays a weather icon for the current condition
- Handles invalid locations and API errors with a clear message

## Built with

- HTML5
- CSS3
- JavaScript (ES6, `async`/`await`, Fetch API, DOM manipulation)
- [WeatherAPI.com](https://www.weatherapi.com/) – current weather endpoint

## How it works

1. The user enters a city and clicks **Get Weather**.
2. `script.js` calls the WeatherAPI.com current-weather endpoint with `fetch` and `async`/`await`.
3. The JSON response is read and the temperature, description, humidity, wind, and icon are shown on the page.
4. If the location isn't found, an error message is shown instead.

## Run locally

```bash
git clone https://github.com/Karthick285/Weather-Finder.git
cd Weather-Finder
```

1. Get a free API key from [weatherapi.com](https://www.weatherapi.com/).
2. Open `script.js` and set your key in the `apiKey` variable.
3. Open `index.html` in your browser.

## Future improvements

- Move the API key to a small backend so it isn't visible in the browser
- 5-day forecast
- Detect the user's location automatically
- Toggle between °C and °F

## Author

**Karthick V** – [GitHub](https://github.com/Karthick285) · [Portfolio](https://karthick285.github.io)
