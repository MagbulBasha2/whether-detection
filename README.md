# Weather App

A simple web application to check the current weather for your location or any city in the world. Built using HTML, CSS, and JavaScript, and powered by the [OpenWeatherMap API](https://openweathermap.org/api).

## Features

- **Your Weather:** Get weather information for your current location using browser geolocation.
- **Search Weather:** Search and view weather details for any city.
- **Weather Details:** Displays city name, country flag, weather description, temperature, windspeed, humidity, and cloudiness.
- **Responsive UI:** Clean and user-friendly interface.

## How It Works

1. **Your Weather Tab:**  
   - Click "Grant Access" to allow the app to use your location.
   - The app fetches your coordinates and displays the weather for your area.

2. **Search Weather Tab:**  
   - Enter a city name and submit.
   - The app fetches and displays weather information for the searched city.

## Technologies Used

- HTML
- CSS
- JavaScript (Vanilla)
- [OpenWeatherMap API](https://openweathermap.org/api)

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/MagbulBasha2/whether-detection.git
   ```
2. Open the project folder.
3. Open `index.html` in your browser.

## Project Structure

```
.
├── index.html
├── styles.css
├── index.js
├── images/
```



## Notes

- You need an API key from [OpenWeatherMap](https://openweathermap.org/api) to fetch weather data. Replace the `API_KEY` in `index.js` with your own if needed.
- The app uses browser session storage to remember your location during the session.

## License

This project is for educational purposes.
