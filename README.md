# Weather App

A simple, responsive web application that provides current weather information for any city using the OpenWeatherMap API. The app features a clean, modern design with dynamic weather icons and real-time data display.

## Features

- **City Search**: Enter any city name to get instant weather updates
- **Current Weather Display**: Shows temperature, humidity, and wind speed
- **Dynamic Weather Icons**: Visual representation of weather conditions (clouds, clear, rain, drizzle, mist)
- **Error Handling**: Displays error message for invalid city names
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Technologies Used

- **HTML5**: Structure and layout
- **CSS3**: Styling with gradients and responsive design
- **JavaScript (ES6)**: API integration and DOM manipulation
- **OpenWeatherMap API**: Weather data source

## How to Use

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Sheshanathan/weather-app.git
   cd weather-app
   ```

2. **Open in Browser**:

   - Simply open `index.html` in your web browser
   - No server setup required for basic functionality

3. **Search for Weather**:
   - Enter a city name in the search box
   - Click the search button or press Enter
   - View the current weather information

## API Key Configuration

⚠️ **Important**: The app currently uses a hardcoded API key for demonstration purposes. For production use:

1. Sign up for a free API key at [OpenWeatherMap](https://openweathermap.org/api)
2. Replace the `apiKey` variable in `index.html` with your own key:
   ```javascript
   const apiKey = "your_api_key_here";
   ```

## Project Structure

```
weather-app/
├── index.html          # Main HTML file with embedded JavaScript
├── style.css           # CSS styles for the application
├── images/             # Weather icons and search button image
│   ├── search.png
│   ├── rain.png
│   ├── clouds.png
│   ├── clear.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── humidity.png
│   └── wind.png
└── README.md           # Project documentation
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the [MIT License](LICENSE).

---

_Built with ❤️ using OpenWeatherMap API_
