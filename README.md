# Weather App

This Weather App is a web application that provides real-time weather information, geolocation data, and additional data from cryptocurrency and news APIs.

## Installation

1. Clone the repository to your local machine
2. Create .env file and write this:
   ```bash
   OPENWEATHER_API_KEY=YOUR_API_KEY

   GOOGLE_MAPS_API_KEY=YOUR_API_KEY
   ```
3. Insert YOUR_API_KEY (from the News API site)
   ```bash
   const newsResponse = await axios.get("https://newsapi.org/v2/top-headlines?country=us&apiKey=YOUR_API_KEY");
   ```
4. Install the required npm packages
   ```bash
   npm install
   ```

## Running the Application
1. Start the server
   ```bash
   node app.js
   ```
2. Open your web browser and go to http://localhost:3000

## Usage
1. Enter a city in the provided search box and click the "Get Weather" button to retrieve real-time weather data.
2. View geographical coordinates based on the entered city.
3. Explore cryptocurrency prices and latest news displayed on the page.

## Dependencies
1. Express: Web application framework.
2. Body Parser: Middleware for parsing POST request data.
3. Bootstrap: Front-end framework for styling.
4. CORS: Middleware for handling Cross-Origin Resource Sharing.

## Server Port
The server runs on port 3000.
