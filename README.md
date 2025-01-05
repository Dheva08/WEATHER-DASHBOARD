# Weather Dashboard

A dynamic and interactive Weather Dashboard built using React.js. This application provides real-time weather updates and forecasts for cities worldwide, leveraging modern design and API integration.

Name: Dhevadharshini
Company: Codtech IT Solutions
ID: CT12IUH
Domain: React.js Web Development
Duration: December 30th 2024 to March 01th of 2025

## Features

- **Real-Time Weather Data**: Displays temperature, humidity, wind speed, and weather conditions.
- **Search Functionality**: Easily search for any city's weather.
- **Dynamic UI**: Backgrounds and visuals change based on the weather.
- **Multi-Day Forecast**: View weather predictions for the upcoming days.
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices.

## Tech Stack

- **React.js**: Frontend framework for building the UI.
- **Weather API**: For fetching weather data.
- **Axios**: For API requests.
- **CSS/TailwindCSS**: Styling the application.
- **React Hooks**: Managing state and side effects.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/weather-dashboard.git
   cd weather-dashboard
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Configure your API key:
   - Sign up on [WeatherAPI]([https://www.weatherapi.com/]) and get an API key.
   - Create a `.env` file in the root directory:
     ```env
     REACT_APP_WEATHER_API_KEY=your_api_key_here
     ```

4. Start the development server:
   ```bash
   npm start
   ```

## Usage

1. Open the application in your browser at `http://localhost:5173`.
2. Enter a city name in the search bar and press Enter.
3. View the current weather and, if implemented, the forecast.

## Folder Structure

```
weather-dashboard/
├── .bolt/
│   └── config.json
├── src/
│   ├── components/
│   │   ├── CurrentWeather.tsx
│   │   ├── Forecast.tsx
│   │   ├── SearchBar.tsx
│   │   └── WeatherBackground.tsx
│   ├── constants/
│   │   └── weatherBackgrounds.ts
│   ├── services/
│   │   └── weatherApi.ts
│   ├── types/
│   │   └── weather.ts
│   ├── utils/
│   │   └── weatherUtils.ts
│   ├── App.tsx
│   ├── index.css
│   ├── main.tsx
│   └── vite-env.d.ts
```

## Dependencies

- React.js
- Axios
- React Icons (optional for icons)
- TailwindCSS or CSS modules (optional for styling)

## Deployment

1. Build the application for production:
   ```bash
   npm run build
   ```
2. Deploy using platforms like:
   - [Netlify](https://www.netlify.com/)
   - [Vercel](https://vercel.com/)
   - [GitHub Pages](https://pages.github.com/)

## Screenshots

_Add screenshots of your application to showcase its features._

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Weather API](https://weatherapi.org/api)
- React.js Documentation

---

Thank you for visiting this repository. Feel free to contribute and make this project even better!
