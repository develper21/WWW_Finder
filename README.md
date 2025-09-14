# 🌤️ Weather Web Suite

A modern, responsive weather application built with React.js that provides real-time weather information for any city worldwide.

[![React](https://img.shields.io/badge/React-17.0.2-blue.svg)](https://reactjs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-Responsive-green.svg)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![OpenWeather API](https://img.shields.io/badge/API-OpenWeather-orange.svg)](https://openweathermap.org/api)

## ✨ Features

- 🌍 **Global Weather Search** - Get weather data for any city worldwide
- 📊 **Comprehensive Weather Data** - Temperature, humidity, pressure, wind speed
- 🌅 **Sunset Information** - Real-time sunset times for searched locations
- 🎨 **Dynamic Weather Icons** - Weather-specific icons that change based on conditions
- 📱 **Responsive Design** - Beautiful UI that works on all devices
- ⚡ **Real-time Updates** - Instant weather information updates
- 🔍 **Smart Search** - Easy city search with auto-focus functionality

## 🖥️ Live Demo

![Weather App Screenshot](https://via.placeholder.com/800x400/4A90E2/FFFFFF?text=Weather+Web+Suite+Demo)

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- OpenWeather API key (free registration required)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/WeatherWebsuite.git
   cd WeatherWebsuite
   ```

2. **Navigate to Frontend directory**
   ```bash
   cd Frontend
   ```

3. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

4. **Get your OpenWeather API key**
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Generate your API key

5. **Configure API key**
   - Open `/Frontend/src/components/weather/temp.js`
   - Replace `a2b003b24344878f781d0e0f9e36b72c` with your API key:
   ```javascript
   let apiKey = "YOUR_API_KEY_HERE";
   ```

6. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

7. **Open your browser**
   - Navigate to [http://localhost:3000](http://localhost:3000)

## 🛠️ Technology Stack

### Frontend
- **React.js** - Modern JavaScript library for building user interfaces
- **JavaScript (ES6+)** - Modern JavaScript features and syntax
- **CSS3** - Styling with responsive design principles
- **Weather Icons** - Beautiful weather-specific iconography

### APIs & Services
- **OpenWeatherMap API** - Real-time weather data provider
- **REST API** - HTTP-based API integration

### Development Tools
- **Create React App** - Zero-configuration React setup
- **npm/yarn** - Package management
- **ESLint** - Code linting and quality assurance

## 📁 Project Structure

```
WeatherWebsuite/
├── Frontend/
│   ├── public/
│   │   ├── index.html
│   │   ├── manifest.json
│   │   └── robots.txt
│   ├── src/
│   │   ├── components/
│   │   │   └── weather/
│   │   │       ├── temp.js          # Main weather component
│   │   │       ├── weathercard.js   # Weather display card
│   │   │       └── style.css        # Weather component styles
│   │   ├── App.js                   # Main App component
│   │   ├── App.css                  # Global app styles
│   │   ├── index.js                 # Application entry point
│   │   └── index.css                # Global styles
│   ├── package.json                 # Dependencies and scripts
│   └── README.md
└── README.md                        # Project documentation
```

## 🎯 Usage

1. **Search for Weather**
   - Enter any city name in the search box
   - Click the "Search" button or press Enter
   - View real-time weather information

2. **Weather Information Displayed**
   - Current temperature in Celsius
   - Weather condition (Clear, Clouds, Haze, Mist, etc.)
   - Location name and country
   - Humidity percentage
   - Atmospheric pressure
   - Wind speed
   - Sunset time
   - Current date and time

## 🔧 Available Scripts

In the project directory, you can run:

### `npm start`
Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Builds the app for production to the `build` folder. Optimized for best performance.

### `npm run eject`
**Note: This is a one-way operation!** Removes the single build dependency and gives you full control over configuration.

## 🌟 Key Features Explained

### Weather Card Component
- Displays comprehensive weather information
- Dynamic weather icons based on conditions
- Responsive layout for all screen sizes
- Real-time data updates

### Search Functionality
- Auto-focus on search input
- Real-time city search
- Error handling for invalid cities
- Instant weather updates

### Weather Icons
- Dynamic icon changes based on weather conditions
- Support for: Clear, Clouds, Haze, Mist, and more
- Beautiful Weather Icons library integration

## 🔑 API Configuration

The application uses the OpenWeatherMap API. To use your own API key:

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
2. Replace the API key in `temp.js`:
   ```javascript
   let apiKey = "YOUR_ACTUAL_API_KEY";
   ```

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Deploy to Netlify/Vercel
1. Build the project
2. Upload the `build` folder
3. Configure environment variables if needed

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather API
- [Weather Icons](https://erikflowers.github.io/weather-icons/) for beautiful weather icons
- [React](https://reactjs.org/) team for the amazing framework
- [Create React App](https://create-react-app.dev/) for the development setup

## 📞 Support

If you have any questions or need help with the project, feel free to:

- Open an issue on GitHub
- Contact me directly
- Check the documentation

---

⭐ **Star this repository if you found it helpful!**

![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red.svg)
![Open Source](https://img.shields.io/badge/Open%20Source-💚-green.svg)
