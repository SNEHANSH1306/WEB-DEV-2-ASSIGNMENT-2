=====================================
      Async Weather Tracker
=====================================

WHAT IS THIS?
-------------
Weather Tracker is a simple weather tracking web app built for learning purposes.
It lets you search any city in the world and instantly see the current
weather conditions like temperature, humidity, wind speed, and more.

It was built as a first-year web development project to practice:
  - HTML structure and layout
  - CSS styling and design
  - JavaScript (async/await, API calls, localStorage)


HOW TO RUN IT
-------------
1. Download or copy all three files into the same folder:
      index.html
      style.css
      script.js

2. Open index.html in any web browser (Chrome, Firefox, Edge, etc.)

3. That's it. No installation needed.


HOW TO USE IT
-------------
1. Type a city name in the search bar at the top (e.g. Delhi, London, Tokyo)
2. Press the Search button or hit Enter on your keyboard
3. The weather for that city will appear on screen
4. Previously searched cities are saved in the sidebar on the right
5. Click any city in the sidebar to search it again quickly


WHAT INFORMATION IS SHOWN
--------------------------
  - City name and country
  - Current temperature (in Celsius)
  - Weather condition (e.g. Clear, Clouds, Rain)
  - Feels Like temperature
  - Humidity percentage
  - Wind speed
  - Atmospheric pressure


FILES IN THIS PROJECT
---------------------
  index.html  -  The structure and content of the webpage
  style.css   -  All the colors, fonts, and layout styling
  script.js   -  All the JavaScript logic (search, fetch, history)


TECHNOLOGIES USED
-----------------
  - HTML5
  - CSS3
  - JavaScript (vanilla, no frameworks)
  - OpenWeatherMap API (free weather data)
  - Google Fonts (Syne, DM Sans)


API INFORMATION
---------------
This app uses the OpenWeatherMap API to fetch weather data.
Website : https://openweathermap.org
The API key is already included in script.js for convenience.
If the key stops working, create a free account at openweathermap.org
and replace the API_KEY value in script.js with your own key.


KNOWN LIMITATIONS
-----------------
  - Requires an internet connection to fetch weather data
  - Search history is saved in the browser only (localStorage)
    so it will be cleared if browser data is wiped
  - City names must be in English


AUTHOR NOTE
-----------
This project was built as a practice exercise for learning
asynchronous JavaScript and working with third-party APIs.
The design uses a dark space-themed UI with deep purple and blue tones.

=====================================
