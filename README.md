# ISS Tracker & Weather Information

A web application that tracks the **International Space Station (ISS)** in real-time using an interactive map, while also displaying weather data at its current location.

## 🌍 Features

- **Real-time ISS Tracking**: Displays the current location of the ISS using the Leaflet.js map library.
- **Custom Marker**: The ISS is represented by a custom PNG marker on the map.
- **Weather Data Integration**: Provides weather information such as temperature, humidity, pressure, and more at the ISS's current location via the OpenWeather API.
- **Automatic Updates**: Fetches new ISS location and weather data every 5 seconds.

## 🚀 Technologies Used

- **JavaScript** for asynchronous API calls.
- **Leaflet.js** for interactive maps and marker management.
- **OpenWeather API** for weather data.
- **ISS API** for real-time satellite location tracking.

## 🛠 How It Works

1. **Map Initialization**: The map is initialized using `Leaflet.js` and tiles from OpenStreetMap.
2. **Custom Marker**: The ISS's location is displayed using a custom marker image.
3. **API Integration**: 
    - **ISS API**: Fetches latitude, longitude, and velocity of the ISS.
    - **OpenWeather API**: Retrieves weather data based on the ISS’s location.
4. **Automatic Updates**: The position of the ISS and corresponding weather data are updated every 5 seconds.

## 💻 Setup Instructions

1. Clone the repository.
   ```bash
   git clone https://github.com/your-username/iss-tracker.git
2. Open APIs.html in a browser to run the application.
