# Lunar.sh

Lunar.sh is a dynamic and visually-rich web dashboard that provides a comprehensive overview of the current state of the moon. It leverages real-time data to present information about the moon's phase, position, and timing, all wrapped in a sleek, space-themed interface that changes based on NASA's Astronomy Picture of the Day.

## ✨ Features

  - **Real-Time Moon Data**: Get up-to-the-minute information on the current moon phase, illumination percentage, age, and distance from Earth.
  - **Dynamic Theming**: The dashboard's color scheme dynamically adapts to the daily NASA Astronomy Picture of the Day (APOD) for a unique visual experience every day.
  - **Positional Awareness**: See the moon's current altitude, azimuth, and visibility from your location.
  - **Key Timings**: Displays local times for moonrise, moonset, and solar noon.
  - **Upcoming Phases**: A grid view of the next four major moon phases and their dates.
  - **Location-Aware**: Automatically detects the user's location to provide accurate data, with a manual override option to search for any city.
  - **Interactive UI**:
      - A visual representation of the moon's current phase.
      - A progress bar showing the moon's position in its orbit between perigee and apogee.
      - User controls for toggling the background blur and switching between 12/24 hour time formats.
  - **Astronomy Picture of the Day**: View information and the story behind the stunning background images provided by NASA.

## 🚀 Getting Started

This is a front-end project and requires no special installation. Simply open the `index.html` file in your web browser.

For the application to fully function, you need to provide your own NASA API key:

1.  Open the `script.js` file.
2.  Find the following line:
    ```javascript
    const NASA_API_KEY = 'Put your NASA API Key here';
    ```
3.  Replace `'Put your NASA API Key here'` with your personal NASA API key. You can get a free key from [NASA's API website](https://api.nasa.gov/).

## 🛠️ Technologies Used

  - **HTML5**
  - **CSS3** (with Custom Properties, Flexbox, and Grid)
  - **JavaScript (ES6+)**
  - **SunCalc.js**: For detailed moon and sun calculations.
  - **ColorThief.js**: To extract a color palette from the daily background image for dynamic theming.

## 🛰️ APIs

  - **NASA APOD API**: Provides the stunning daily astronomy pictures that serve as the application's background.
  - **Nominatim (OpenStreetMap)**: Used for reverse geocoding to identify city and country names from geographic coordinates.
  - - This ain´t working...
  - **Browser Geolocation API**: To get the user's current location for accurate celestial data.

## 🙏 Credits

  - **Celestial Data**: Powered by the NASA APOD API and SunCalc.js.
  - **Favicon**: Provided by Icons8.
