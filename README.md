# Real-time Weather Dashboard

Create a real-time weather dashboard using Ballerina that displays weather information for different cities. The dashboard will allow users to search for a city and view its current weather conditions and forecast. To achieve this, you'll integrate with a weather API to fetch the necessary data.

Features:

// This code displays the current weather information for a given city.
// It also updates the dashboard when the weather data changes.
// The user can set their preferences, such as the temperature unit and the default city.



- City Search: Users should be able to enter the name of a city in a search box and get the current weather information for that city.
- Weather Details: Display relevant weather details, such as temperature, humidity, wind speed, weather description, etc., for the selected city.
- Forecast: Show a 5-day weather forecast for the chosen city, including high and low temperatures for each day.
- Real-time Updates: Implement real-time updates for weather data. When the data for a specific city changes, the dashboard should automatically update without requiring a page refresh.
- User Preferences: Allow users to set their preferences, such as the temperature unit (Celsius/Fahrenheit) and the default city to display on the dashboard.
- Error Handling: Handle errors gracefully, such as when the API is unavailable or when the user enters an invalid city name.

Technologies and Tools:

- Ballerina: Use Ballerina to build the backend for fetching weather data and processing user requests.
- Weather API: Choose a public weather API that provides real-time weather data. Some examples include OpenWeatherMap, Weather API, or Weatherstack.
- WebSocket: Implement WebSocket to achieve real-time updates on the weather dashboard.
- Frontend: For the frontend, you can use web technologies like HTML, CSS, and JavaScript or a frontend framework like React, Vue.js, or Angular.
- Database (Optional): If you want to add user preference settings, you can use a lightweight database like SQLite.

Learning Objectives:

- Working with APIs: Learn how to make HTTP requests and handle API responses in Ballerina.
- Microservices: Understand how to build microservices using Ballerina's support for networked communication.
- Real-time Communication: Learn about WebSocket communication for real-time updates.
- Error Handling: Practice handling errors and exceptions in Ballerina.
- Persistence (Optional): If you choose to add a database, you'll get experience with database interactions in Ballerina.
