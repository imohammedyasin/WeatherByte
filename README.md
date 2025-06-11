# WeatherByte 🌦️

WeatherByte is a sleek and responsive weather web app built with **HTML**, **CSS**, and **JavaScript**, which allows users to search for real-time weather data of any city using the **OpenWeatherMap API**.

## 🚀 Features

- 🔍 Search for any city’s weather
- 🌡️ Displays temperature in Celsius
- 💨 Shows wind speed and humidity
- 🖼️ Dynamic weather icons based on condition (Clouds, Clear, Rain, etc.)
- ⚠️ Displays error message for invalid city names

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- JavaScript (ES6)  
- OpenWeatherMap API

## 📂 Project Structure

```
WeatherByte/
├── index.html
├── style.css
├── images/
│   ├── clouds.svg
│   ├── clear.svg
│   ├── rain.svg
│   ├── drizzle.svg
│   ├── mist.svg
│   ├── snow.svg
│   ├── search.png
│   ├── humidity.svg
│   └── wind.svg
```

## ⚙️ How to Use

1. Download or clone this project.
2. Open the `index.html` file in your browser.
3. Type a city name and click the search button.
4. View current weather data fetched live from OpenWeatherMap.

## 🔐 API Key

Replace the default API key with your own from [OpenWeatherMap](https://openweathermap.org/api) in `index.html`:

```javascript
const apiKey = "YOUR_API_KEY_HERE";
```

## 📌 Notes

- Ensure internet connectivity to fetch live weather data.
- This project uses the free OpenWeatherMap API, which has usage limits.
- Icons and styling can be customized to fit your preferences.

## ✍️ Author

Made with 💻 by [Your Name Here]
