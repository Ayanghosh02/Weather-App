# Weather-App
This repository contains a simple weather application built using HTML, CSS, and JavaScript. It allows users to view weather information based on their current location or search for weather data by city name.
Files:

    weather.html: Contains the structure and content of the weather app user interface. It includes tabs for switching between viewing the user's current weather and searching for weather by city name.

    weather.css: Defines the styles and layout of the weather app UI. It uses custom CSS variables for colors and responsive design techniques to ensure the app looks good on different devices.

    weather.js: Implements the functionality of the weather app using JavaScript. It includes:
        Switching between tabs for user weather and search weather functionality.
        Fetching weather data from the OpenWeather API based on user geolocation or city name input.
        Displaying loading indicators and error messages for better user experience.
        Rendering weather information such as temperature, wind speed, humidity, and cloudiness dynamically on the UI.

    images/: Directory containing images used in the app, including icons for weather conditions and location.

Functionality:

    Tab Navigation: Users can switch between "YOUR WEATHER" and "SEARCH WEATHER" tabs to view weather information either based on their current location or by searching for a city.

    Location Access: The app prompts users to grant geolocation access. If granted, it fetches weather data based on the user's current coordinates.

    Search Functionality: Users can enter a city name into the search input to fetch and display weather data for that city.

    Responsive Design: The app is designed to be responsive, adapting to different screen sizes and orientations for a consistent user experience across devices.

Usage:

To use the app:

    Open index.html in a web browser.
    Grant location access when prompted or use the search form to look up weather data for specific cities.
    View weather details including temperature, wind speed, humidity, and cloudiness displayed in a visually appealing format.

Notes:

    This project uses the OpenWeather API (https://openweathermap.org/api) for fetching weather data. You will need an API key to use the service.
    Customize the design and functionality further based on your preferences or additional requirements.

Contributing:

Feel free to fork this repository, make improvements, and submit pull requests. Contributions and feedback are welcome to enhance the app's functionality, design, or performance.
