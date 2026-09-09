# Weather Dashboard

A responsive weather dashboard built with React that allows users to search for cities and view current weather conditions and a multi-day forecast.

## Live Demo

https://omargomaa702.github.io/Weather-Dashboard/

## About The Project

Weather Dashboard is a React-based weather application that provides real-time weather information for cities around the world.

Users can search for a city using an autocomplete search field and view:

- Current temperature
- Weather condition
- Weather description
- Feels-like temperature
- Humidity
- Wind speed
- Pressure
- Sunrise and sunset
- Daily weather forecast

The application uses external APIs to retrieve city and weather data.

## Features

- City search with autocomplete
- Real-time weather data
- Current weather information
- Multi-day weather forecast
- Weather icons
- Responsive design
- Loading state
- Error handling
- Dynamic city selection

## Technologies Used

- React
- Vite
- JavaScript
- CSS
- OpenWeather API
- GeoDB Cities API
- React Select
- React Async Paginate

## APIs

### OpenWeather API

Used to retrieve:

- Current weather data
- Weather conditions
- Temperature
- Humidity
- Wind information
- Forecast data

### GeoDB Cities API

Used for city search and autocomplete functionality.

## Project Structure

```text
Weather-Dashboard/
│
├── public/
│   └── icons/
│
├── src/
│   ├── components/
│   │   ├── CurrentWeather/
│   │   ├── Forecast/
│   │   └── Search/
│   │
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── index.html
├── package.json
├── vite.config.js
└── README.md
