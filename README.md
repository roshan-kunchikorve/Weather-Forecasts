# Weather App
 
A simple, dark-themed web app that lets you look up the current weather for any city using the OpenWeatherMap API.
 
## Features
 
- Search current weather by city name
- Displays city name, temperature (°C), and a short weather description
- Clean, minimal dark UI
- Friendly error message when a city isn't found
## Tech Stack
 
- HTML5
- CSS3 (vanilla, no frameworks)
- JavaScript (vanilla, ES6+)
- [OpenWeatherMap API](https://openweathermap.org/api)
## Project Structure
 
```
.
├── index.html    # App markup
├── styles.css    # Styling
└── scripts.js    # Weather-fetching logic and DOM handling
```
 
## Getting Started
 
1. Clone or download this repository.
2. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api).
3. Open `scripts.js` and set your API key:
```js
   const API_KEY = "your_api_key_here";
```
4. Open `index.html` in your browser (no build step or server required).
## Usage
 
1. Type a city name into the input field.
2. Click **Get Weather**.
3. The current temperature and weather description will appear, or an error message if the city isn't found.

## License
 
This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
