# Weatherly ⛅

A simple, clean weather app that shows live weather for any city in the world. Built with pure HTML, CSS, and JavaScript — no frameworks, no libraries, no API key required.

## 🔗 Live Demo

👉 **[Try it here](https://vsbharath555.github.io/weather-app/)**

## ✨ Features

- 🔍 Search weather for any city worldwide
- 🌡️ Live temperature with "feels like" reading
- 💧 Humidity and 💨 wind speed details
- ⛅ Weather emoji that changes with conditions (rain, snow, thunderstorm, etc.)
- ⌨️ Press Enter to search — no need to click the button
- ⚠️ Friendly error messages for invalid city names or network issues
- 📱 Responsive design — works on mobile and desktop

## 🛠️ Built With

- **HTML5** — structure
- **CSS3** — glassmorphism card design with gradient background
- **JavaScript (ES6+)** — async/await, Fetch API, DOM manipulation
- **[Open-Meteo API](https://open-meteo.com/)** — free weather data, no API key needed

## ⚙️ How It Works

1. **Geocoding** — the city name you type is converted into latitude/longitude coordinates using the Open-Meteo Geocoding API
2. **Weather fetch** — those coordinates are sent to the Open-Meteo Forecast API to get current conditions
3. **Display** — JavaScript updates the page with temperature, humidity, wind speed, and a matching weather emoji

## 🚀 Run It Locally

1. Clone the repository:
   ```
   git clone https://github.com/vsbharath555/weather-app.git
   ```
2. Open `index.html` in your browser — that's it! No installation or setup needed.

## 📸 Screenshot

*(Add a screenshot of your app here — while editing this README on GitHub, just drag an image into the editor and it uploads automatically)*

## 🔮 Future Improvements

- [ ] 5-day weather forecast
- [ ] Auto-detect user's location using browser geolocation
- [ ] Background color changes based on weather conditions
- [ ] Toggle between °C and °F

## 👤 Author

**Bharath V S**
- GitHub: [@vsbharath555](https://github.com/vsbharath555)
- LinkedIn: *(add your LinkedIn profile link here)*

---

⭐ If you found this project helpful, give it a star!
